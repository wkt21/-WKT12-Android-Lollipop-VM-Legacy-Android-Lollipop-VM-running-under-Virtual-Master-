tell application "UTM"
    -- specify boot ISO
    set iso to POSIX file "/path/to/ubuntu.iso"

    -- create QEMU VM (ARM64) with 64GiB drive
    set vm to make new virtual machine with properties ¬
        {backend:qemu, configuration:{name:"QEMU ARM64", architecture:"aarch64", ¬
        drives:{{removable:true, source:iso}, {guest size:65536}}}}

    -- duplicate VM and disable hypervisor
    duplicate vm with properties {configuration:{name:"Duplicate QEMU ARM64", hypervisor:false}}

    -- create Apple VM (macOS 13+)
    make new virtual machine with properties ¬
        {backend:apple, configuration:{name:"Apple Linux", ¬
        drives:{{removable:true, source:iso}, {guest size:65536}}}}
end tell

tell application "UTM"
    -- list all virtual machines
    set vms to virtual machines

    -- get VM by name
    set vm to virtual machine named "Ubuntu"

    -- get VM by ID
    set vm to virtual machine id "5D419106-2824-4FED-BFE1-24A7F7E253D8"
end tell

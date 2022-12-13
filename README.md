# xakra_skillbar

# Description
Skillbar imported from FiveM, adapted to RedM for use in scripts. Changed key detection to be more accurate.

To modify the color you must modify the file 'html/style.css' line 56 and 57.

# How to use
```lua
    local Skillbar = exports['xakra_skillbar']:GetSkillbarObject()
    Skillbar.Start({
        duration = math.random(800, 1500), -- how long the skillbar runs for
        pos = math.random(20, 65), -- how far to the right the static box is
        width = math.random(12, 14), -- how wide the static box is
    }, function()
        print('done')
        
    end, function()
        print('fail')
    end)              
```

![image](https://user-images.githubusercontent.com/107937295/207393373-e377f6d9-9856-411d-b282-d1d4d4ca1489.png)

## Instructions to incorporate script
- Copy the script into a folder (to choose) from the 'resources' folder.
- Add 'ensure xakra_skillbar' in the 'resources.cfg' document.




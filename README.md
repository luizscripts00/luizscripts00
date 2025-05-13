lua
getgenv().simple_settings = {
    ["MASTERY"] = { -- Settings related to leveling up weapon or skill mastery
        ["ACTIVE"] = true, -- Enable or disable mastery leveling (true = enabled, false = disabled)
        ["METHOD"] = "Half", -- Method for gaining mastery, "Half"[350] or "Full"[600]
    },

    ["OBJECTIVE"] = { -- Goals for farming and unlocking features
        ["SUPERHUMAN"] = true, -- Automatically unlock the "Superhuman" fighting style
        ["RACE-CONFIGURE"] = {
            ["RACE"] = {"Human", "Skypiea", "Fishman", "Mink"}, -- List -- "Human", "Skypiea", "Fishman", "Mink"
            ["RACE-LOCK"] = true, -- Automatically change the character race if not in the list
            ["RACE-V3"] = true, -- Automatically upgrade character race to V3 if possible Human, Mink, (Fishman, Ghoul, Cyborg) soon
        },

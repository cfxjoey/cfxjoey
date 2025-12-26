Joey = {
    Graduation = 2027,
    Languages = {
        "JavaScript", "Node.js", "Express.js", "MySQL",
        "Lua", "C#", "HTML/CSS", "PHP", "Java", "Python"
    },
    Hobbies = {
        "Scripting for FiveM",
        "Learning new languages",
        "Gaming",
        "Experimenting with fun projects"
    },
    LegendaryStatus = true
}

-- Activate legendary mode
while Joey.LegendaryStatus do
    Wait(0)
    print("⚡ Legendary Joey in action!")
    print("💡 Skills ready: " .. table.concat(Joey.Languages, ", "))
end

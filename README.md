# What is this?
This is a prompter for CLI`s. You provide a QUESTIONS array and it prompts it to the user.

# Example Usage
```
    const cli_prompt = require("cli-question-prompt");

    let questions = []
    questions.push({
    type: "input",
    message: "Please enter your name",
    name: "name",
    default: "Unknown-Man"
})

let answers = await cli_prompt.prompt(questions)
console.log(`My name is: ${answers.name}`)
```

# PLEASE NOTE
This package uses other packages to function, and I **DO NOT** claim to be the owner of all this packages!
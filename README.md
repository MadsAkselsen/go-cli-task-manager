# go-cli-task-manager

#### install

`go install .` for global commands
`go build .` in root folder for a binary. Then run `./go-cli-task-manager`

#### commands

Add tasks: `./go-cli-task-manager add mytask`
Remove tasks: `./go-cli-task-manager do mytask`
List all tasks: `./go-cli-task-manager list`

#### use cobra package

`go install github.com/spf13/cobra-cli@latest` for install

`cobra-cli` for help

`cobra-cli add do` to add command "do"

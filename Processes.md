
[ps](#ps)
[pstree](#pstree)
[top](#top)
[free](#free)
[kill](#kill)
[killall](#killall)
[nohup](#nohup)

### ps

The `ps` command gives a list of the processes currently running on the system.
Without parameter, it will restrict the processes on current shell only.

Options:
- **x**: To view all the processes belonging to the user
- **u**: Shows the process owner
- **a**: All processes for all users
- **l**: Additional information such as PPID and UID.

### pstree

To see the process hierachy.

`$pstree -apuh`

Options:
- **a**: Shows the parameters with which the programs are running.
- **h**: 
- **p**: Output the process id
- **u**: shows the user

### top

Shows continuously processes, cpu hogs, etc.

### free

Show memory status.

### kill

Sends the signal

Options:

- **-l**: Shows all the options

### killall

Same as kill but pass the processname

`$killall -TERM bash`

eg:
`$kill -19 9201`

### nohup

Nohup is used to create the detached process.

`$nohup ping google.com &`
# PROGRAM 4 : PROCESS CREATION AND MANAGEMENT USING LINUX SYSTEM CALLS

## AIM :
To study process creation, execution, and synchronization using Linux process system calls:
• fork()
• exec()
• wait()
• getpid()
• getppid()
and to understand parent-child process relationships.

## CONTEXT :
A process is a program that is currently being executed. Linux allows a process to create another process (called a child process) and manage its execution.

## LINUX SYSTEM CALLS USED :

| System Call | Function |
|---|---|
| `fork()` | Creates a new child process by duplicating the current (parent) process. |
| `getpid()` | Returns the Process ID (PID) of the currently executing process. |
| `getppid()` | Returns the Process ID (PID) of the parent process. |
| `wait()` | Suspends the parent process until the child process terminates. |
| `sleep()` | Suspends the execution of the current process for the specified number of seconds. *(Library function that internally uses kernel timing services; often included in OS labs.)* |

## SOURCE CODE (Process Creation) :
**File:** [forkDemo.c](https://github.com/112514022/osLab/blob/c9c806460130ab3b2c7e3cef5fb28e57b5966946/oslab/ex04/ProcessCreation/forkDemo.c)

## COMPILATION :

```bash
gcc forkDemo.c -o forkDemo
```

## EXECUTION :

```bash
./forkDemo
```
## OUTPUT :
![Output for Experiment 4_1](https://github.com/112514022/osLab/blob/7a67943c380d45027756cd5171d4288a0a07b6ff/oslab/ex04/ProcessCreation/image.png)

## SOURCE CODE (Process Management) :
**File:** [waitDemo.c](https://github.com/112514022/osLab/blob/2cca677c4f99100362b23567215c0b05742559f0/oslab/ex04/ProcessManagement/waitDemo.c)

## COMPILATION :

```bash
gcc waitDemo.c -o waitDemo
```

## EXECUTION :

```bash
./waitDemo
```

## OUTPUT :
![Output for Experiment 4_2](https://github.com/112514022/osLab/blob/6d6069b6059cab0affeaea27c3fa3bea7f0779c3/oslab/ex04/ProcessManagement/image.png)

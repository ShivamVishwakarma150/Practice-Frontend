# Linux Intro
Linux is an open-source operating system kernel initially created by Linus Torvalds in 1991. Since then, it has grown to become one of the most widely used operating systems worldwide, powering everything from personal computers to servers, mobile devices, and even supercomputers.

Here are some key points about Linux:

1. **Open Source**: One of the defining characteristics of Linux is its open-source nature. This means that the source code of the operating system is freely available for anyone to view, modify, and distribute. This openness has fostered a vibrant community of developers and users who contribute to its development.

2. **Distributions**: Linux is not just one operating system but a family of operating systems, known as distributions or "distros." Each distribution typically includes the Linux kernel along with a collection of software applications and tools tailored to specific needs. Examples of popular Linux distributions include Ubuntu, Fedora, Debian, and CentOS.

3. **Kernel**: At its core, Linux is a kernel that interacts directly with the hardware of a computer, managing system resources such as CPU, memory, and storage. The Linux kernel serves as the foundation upon which various distributions are built.

4. **Command Line Interface**: Linux offers a powerful command-line interface (CLI) that allows users to interact with the system directly through text-based commands. While this can be intimidating for beginners, mastering the command line can provide greater control and flexibility over the system.

5. **Graphical User Interface (GUI)**: Most Linux distributions also offer a graphical user interface, similar to Windows or macOS, making it more accessible to users who prefer a point-and-click interface. Popular desktop environments for Linux include GNOME, KDE, and XFCE.

6. **Security**: Linux is renowned for its robust security features. Its permission-based access control and inherent design principles make it less susceptible to malware and other security threats compared to other operating systems.

7. **Flexibility and Customization**: One of the strengths of Linux is its flexibility and customization options. Users can tailor their Linux experience to suit their preferences by choosing different distributions, desktop environments, and software packages.

In summary, Linux is a powerful, flexible, and customizable operating system that has gained widespread adoption due to its open-source nature, security features, and community-driven development. Whether you're a beginner or an experienced user, Linux offers something for everyone and continues to evolve with the changing needs of the computing world.

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

# Linux distributions
Linux distributions, or "distros," are different variations of the Linux operating system that package together the Linux kernel with various software components, libraries, and utilities to create a complete operating system. While they share the same core Linux kernel, each distribution offers a unique user experience, design philosophy, and set of pre-installed software. Here are some key differences between popular Linux distributions:

1. **Package Management**:
   - **Debian-based**: Uses `apt` (Advanced Package Tool) for package management. Examples include Debian itself, Ubuntu, and Linux Mint.
   - **Red Hat-based**: Uses `yum` (Yellowdog Updater, Modified) or `dnf` (Dandified Yum) for package management. Examples include Fedora, CentOS, and Red Hat Enterprise Linux (RHEL).

2. **Release Cycle**:
   - **Fixed Release**: Distributions like Ubuntu and Fedora follow a fixed release cycle where a new version is released at regular intervals (e.g., every 6 months or 1 year).
   - **Rolling Release**: Distributions like Arch Linux and openSUSE Tumbleweed use a rolling release model where updates are continuously rolled out, offering the latest software versions without the need for major version upgrades.

3. **Desktop Environments**:
   - Different distributions offer a variety of desktop environments, such as GNOME, KDE Plasma, XFCE, LXDE, and more. Some distributions focus on providing a specific desktop environment by default, while others offer a choice during installation.

4. **Target Audience**:
   - **General-Purpose**: Distributions like Ubuntu and Fedora are designed for general-purpose use and aim to provide a balance of usability, stability, and features.
   - **Specialized**: Some distributions are tailored for specific use-cases, such as server management (e.g., CentOS, RHEL), penetration testing (e.g., Kali Linux), or lightweight systems (e.g., Puppy Linux, Bodhi Linux).

5. **Philosophy and Community**:
   - Each distribution has its own philosophy and community-driven development model. For example, Debian prioritizes free and open-source software, while Fedora focuses on innovation and adopting new technologies.

6. **Default Software**:
   - Distributions come with different sets of pre-installed software, ranging from office productivity tools, web browsers, media players, development tools, and more. This can influence the out-of-the-box experience for users.

7. **Support and Documentation**:
   - The level of community support, documentation, and enterprise support varies between distributions. Some distributions have extensive documentation and large communities, making it easier for users to find help and resources.

8. **Security Features**:
   - While Linux in general is known for its security, different distributions may implement additional security features, policies, and practices to enhance system security.

Choosing the right distribution depends on your specific needs, preferences, and level of expertise. Whether you're looking for a beginner-friendly system, a lightweight environment, a server operating system, or a platform for customization and learning, there's likely a Linux distribution that fits your requirements.

# REPL

A REPL, which stands for Read-Eval-Print Loop, is an interactive programming environment that allows users to enter commands, have them executed, and see the results immediately. It's a common feature in many programming languages, interpreted languages in particular.

Here's a breakdown of what happens in a REPL:

- **Read**: The REPL reads the user's input (e.g., code or commands).
  
- **Eval**: The REPL evaluates the input and executes it.

- **Print**: The REPL prints the result of the executed command or expression.

- **Loop**: The process repeats, allowing the user to enter more commands.

Some popular programming languages that have REPL environments include:

- **Python**: Accessed using the `python` or `python3` command.
  
  ```python
  >>> print("Hello, World!")
  Hello, World!
  ```

- **JavaScript**: Accessed using the Node.js REPL with the `node` command.
  
  ```javascript
  > console.log("Hello, World!");
  Hello, World!
  ```

- **Ruby**: Accessed using the `irb` (Interactive Ruby) command.
  
  ```ruby
  irb(main):001:0> puts "Hello, World!"
  Hello, World!
  ```

- **Scala**: Accessed using the `scala` command.
  
  ```scala
  scala> println("Hello, World!")
  Hello, World!
  ```

REPLs are great for testing out code snippets, exploring language features, and debugging. They provide immediate feedback, making them a valuable tool for developers and learners alike.

<br>
<br>
<br>
<br>

# Commands in Linux

These commands are basic commands used in a Unix-like shell (e.g., bash) to navigate and interact with the file system. Here's a brief explanation of each command:

1. **`pwd`**:
   - Stands for "Print Working Directory."
   - Displays the current directory or path of the working directory.
  
   ```bash
   $ pwd
   /home/user
   ```

2. **`ls`**:
   - Stands for "List."
   - Lists the files and directories in the current directory.
  
   ```bash
   $ ls
   file1.txt directory1 file2.txt
   ```

3. **`cd`**:
   - Stands for "Change Directory."
   - Changes the current directory to the specified directory.
   - Without any arguments, it changes to the home directory.

   ```bash
   $ cd
   ```

4. **`cd ..`**:
   - Moves up one directory level from the current directory.

   ```bash
   $ cd ..
   ```

5. **`cd ../..`**:
   - Moves up two directory levels from the current directory.

   ```bash
   $ cd ../..
   ```

6. **`cd ~`**:
   - Changes the current directory to the home directory of the current user.

   ```bash
   $ cd ~
   ```

7. **`cd directory1/directory2`**:
   - Changes the current directory to `directory2` inside `directory1`.

   ```bash
   $ cd directory1/directory2
   ```

These commands are fundamental for navigating the file system, listing directory contents, and changing the current working directory in a Unix-like shell.

<br>
<br>
<br>
<br>
<br>

# Understanding File Paths and Directory Navigation in Unix-like Systems

Here some important concepts related to file paths and directory navigation in Unix-like operating systems. Let me elaborate a bit on the points you've mentioned:

1. **Tilde (`~`) Symbol**:
   - The tilde (`~`) symbol represents the home directory of the current user.
   - Using `~` allows you to specify paths relative to the home directory, making it a convenient shortcut.
   - For example, `cat ~/main.html` reads the `main.html` file located in the home directory of the current user.

2. **Relative Path**:
   - A relative path describes the location of a file or directory relative to the current working directory.
   - It does not start with a slash (`/`) and navigates the directory structure based on the current location.
   - For example, if you are in the `/home/user` directory, and you have a file named `example.txt` in a subdirectory named `docs`, the relative path to `example.txt` would be `docs/example.txt`.

3. **Absolute Path**:
   - An absolute path specifies the complete location of a file or directory starting from the root directory (`/`) or the home directory (`~`).
   - It always starts with a slash (`/`) and provides the full directory path.
   - For example, `/home/user/docs/example.txt` is an absolute path to the `example.txt` file located in the `docs` subdirectory of the `user` directory.

4. **`cd /` vs `cd ~`**:
   - **`cd /`**: Changes the current directory to the root directory of the file system.
   - **`cd ~`**: Changes the current directory to the home directory of the current user.
  
   ```bash
   $ cd /
   ```

   ```bash
   $ cd ~
   ```

Understanding the difference between relative and absolute paths is crucial for effective navigation and management of files and directories in a Unix-like environment. Relative paths are often used for local navigation within a directory structure, while absolute paths provide the full path to locate files or directories from any location in the file system.

<br/>
<br/>
<br/>


### Absolute Path

An absolute path specifies the full location of a file or directory from the root directory. It starts with the root directory (`/` on Unix-like systems or `C:\` on Windows) and includes all directories leading up to the target file or directory.

**Unix-like Systems (Linux, macOS)**
```bash
/home/user/documents/file.txt
```
- `/` indicates the root directory.
- `home` is a directory inside the root directory.
- `user` is a directory inside `home`.
- `documents` is a directory inside `user`.
- `file.txt` is the target file inside `documents`.

**Windows**
```bash
C:\Users\User\Documents\file.txt
```
- `C:\` indicates the root directory.
- `Users` is a directory inside the root directory.
- `User` is a directory inside `Users`.
- `Documents` is a directory inside `User`.
- `file.txt` is the target file inside `Documents`.

### Relative Path

A relative path specifies the location of a file or directory relative to the current working directory. It doesn't start with the root directory but navigates from where you currently are.

Suppose you are currently located in the directory `/home/user` (Unix-like) or `C:\Users\User` (Windows).

**Unix-like Systems (Linux, macOS)**
```bash
cd documents
```
This relative path means "go to the `documents` directory from the current directory (`/home/user`)".

**Windows**
```bash
cd Documents
```
This relative path means "go to the `Documents` directory from the current directory (`C:\Users\User`)".

Another example:

If you're in `/home/user` (Unix-like) or `C:\Users\User` (Windows), and you want to access a file named `file.txt` inside the `documents` directory which is inside `user`, you can use a relative path like:

**Unix-like Systems**
```bash
cd documents
cat file.txt
```

**Windows**
```bash
cd Documents
type file.txt
```

In both cases, the relative path is interpreted based on the current working directory.

<br/>
<br/>
<br/>

These are commonly used `ls` command options in Unix-like systems (Linux, macOS). Let me explain each of them:

### `ls -l`

The `ls -l` command lists files and directories in long format. It provides detailed information about the files and directories, including permissions, number of links, owner, group, size, and modification date.

Example output:
```bash
-rw-r--r-- 1 user user 1234 Apr 17 10:00 file.txt
drwxr-xr-x 2 user user 4096 Apr 17 09:59 directory
```

### `ls -a`

The `ls -a` command lists all files and directories, including hidden ones. Hidden files and directories in Unix-like systems start with a dot (`.`).

Example output:
```bash
.  ..  .hiddenfile  file.txt  directory
```

In this example, `.hiddenfile` is a hidden file, and `.` and `..` represent the current directory and parent directory, respectively.

### `ls -lh`

The `ls -lh` command lists files and directories in long format with human-readable file sizes. It displays file sizes in a format that is easier to read, such as KB, MB, or GB, depending on the size.

Example output:
```bash
-rw-r--r-- 1 user user 1.2K Apr 17 10:00 file.txt
drwxr-xr-x 2 user user 4.0K Apr 17 09:59 directory
```

### `ls --help`

The `ls --help` command displays the help manual for the `ls` command. It provides information on how to use the `ls` command and lists all the available options and their descriptions.

Example output:
```bash
Usage: ls [OPTION]... [FILE]...
List information about the FILEs (the current directory by default).
Sort entries alphabetically if none of -cftuvSUX nor --sort is specified.

Mandatory arguments to long options are mandatory for short options too.
  -a, --all                  do not ignore entries starting with .
  -l                         use a long listing format
  -h, --human-readable       with -l and/or -s, print human readable sizes (e.g., 1K 234M 2G)
      --help                 display this help and exit
```

This help output provides a summary of the `ls` command options and how to use them.

<br/>
<br/>


# Some More Commands

### `mkdir`

The `mkdir` command stands for "make directory." It is used to create a new directory (folder) in the file system.

**Example:**
```bash
mkdir folder_name
```
This command will create a new directory named `folder_name` in the current working directory.

### `touch`

The `touch` command is used to create a new empty file in the file system.

**Example:**
```bash
touch file.txt
```
This command will create a new empty file named `file.txt` in the current working directory.

### `cat`

The `cat` command is used to read, concatenate, and display the contents of a file on the standard output.

**Example:**
```bash
cat file.txt
```
This command will display the contents of `file.txt` on the terminal.

### `rm`

The `rm` command stands for "remove." It is used to delete files and directories.

**Remove a file:**
```bash
rm file.txt
```
This command will delete the `file.txt` from the file system.

### `rmdir`

The `rmdir` command stands for "remove directory." It is used to delete an empty directory from the file system.

**Example:**
```bash
rmdir folder_name
```
This command will delete the directory named `folder_name` if it is empty.

### `rm -r subfolder`

The `rm -r` command is used to delete a directory and its contents recursively. The `-r` flag stands for "recursive."

**Example:**
```bash
rm -r subfolder
```
This command will delete `subfolder` and all its contents recursively.

### `rm -rf subfolder`

The `rm -rf` command is similar to `rm -r`, but it forces the removal without prompting for confirmation. The `-f` flag stands for "force."

**Example:**
```bash
rm -rf subfolder
```
This command will forcefully delete `subfolder` and all its contents without any confirmation prompts.

### `rm -rf /`

The `rm -rf /` command is extremely dangerous. It attempts to delete everything from the root directory (`/`), effectively wiping out the entire file system.

**Warning:** Running this command can cause irreversible damage to your system, leading to data loss and making your system unusable.

**Example:**
```bash
rm -rf /
```
This command is critical and should never be executed unless you are absolutely sure about what you are doing and understand the consequences.

Always exercise caution when using these commands, especially with the `rm -rf /` command, to avoid unintentional data loss or system damage.

<br/>
<br/>
<br/>

# Vi Editor
The `vi` editor is a widely used text editor on Unix-like systems, such as Linux and macOS. It stands for "Visual Editor." `vi` has two main modes: **command mode** and **insert mode**. Here's a detailed overview of `vi`:

### Starting `vi`

To start editing a file with `vi`, you can use the following command:
```bash
vi filename
```
Replace `filename` with the name of the file you want to edit. If the file does not exist, `vi` will create a new file with that name when you save it.

### Modes in `vi`

#### Command Mode

When you open a file with `vi`, you are initially in command mode. In this mode, you can navigate through the file, search for text, and perform various editing operations.

#### Insert Mode

To switch from command mode to insert mode, press `i`. In insert mode, you can type and edit text as you would in any other text editor.

To switch back to command mode from insert mode, press `Esc`.

### Basic Navigation in Command Mode

- **Move the cursor**: Arrow keys (`←`, `→`, `↑`, `↓`)
- **Move to the beginning of the line**: `0`
- **Move to the end of the line**: `$`
- **Move to the beginning of the document**: `gg`
- **Move to the end of the document**: `G`

### Basic Editing in Command Mode

- **Delete a character**: `x`
- **Delete a line**: `dd`
- **Undo the last change**: `u`
- **Redo the last undone change**: `Ctrl + r`

### Saving and Exiting

- **Save changes**: `:w`
- **Save changes and exit**: `:wq` or `ZZ`
- **Exit without saving**: `:q!`
- **Save and exit**: Press `Esc` to ensure you are in command mode, then type `:wq` and press `Enter`.

### Searching and Replacing

- **Search for text**: `/search_term`
  - To find the next occurrence, press `n`.
  - To find the previous occurrence, press `N`.
- **Replace text**: `:s/search_term/replacement_text/g`
  - Replace all occurrences in the current line: `:%s/search_term/replacement_text/g`

### Additional `vi` Commands

- **Copy (yank) a line**: `yy`
- **Paste (put) copied line**: `p`
- **Cut (delete) a line**: `dd`
- **Copy (yank) selected text**: `y`
- **Cut (delete) selected text**: `d`
- **Paste selected text**: `p`

### Exiting `vi`

- **Exit without saving changes**: `:q!`
- **Save changes and exit**: `:wq` or `ZZ`

Remember, `vi` can be quite powerful once you get used to its commands, but it has a steep learning curve. It might take some time to get comfortable with its various modes and commands, but with practice, it becomes a powerful tool for editing text files efficiently in Unix-like environments.

In `vi` (and its improved version, `vim`), the keys `h`, `j`, `k`, and `l` are used for basic navigation while in normal mode. Here's what each of these keys does:

- **`h`**: Moves the cursor one character to the left.
- **`j`**: Moves the cursor down one line.
- **`k`**: Moves the cursor up one line.
- **`l`**: Moves the cursor one character to the right.

### Basic Navigation with `h`, `j`, `k`, `l`

- **Left**: Press `h` to move the cursor to the left.
- **Down**: Press `j` to move the cursor down.
- **Up**: Press `k` to move the cursor up.
- **Right**: Press `l` to move the cursor to the right.

These keys are quite intuitive once you get used to them and can make navigating and editing text in `vi` or `vim` much faster once you're comfortable with their use.

<br/>
<br/>
<br/>

In `vi` (and `vim`), the `w` command is used for navigating forward by words, while `d` is used for deleting text. Let's break down these commands:

### `w`, `2w`, `3w`, ...

- **`w`**: Moves the cursor forward to the beginning of the next word.
- **`2w`**: Moves the cursor forward to the beginning of the second next word.
- **`3w`**: Moves the cursor forward to the beginning of the third next word.
- ... and so on.

### Example:

Suppose you have the following text:
```
This is a sample text to demonstrate vi commands.
```

- If the cursor is at the beginning (`T`), pressing `w` will move it to the beginning of `is`.
- Pressing `2w` will move it to the beginning of `a`.
- Pressing `3w` will move it to the beginning of `sample`.

### `d2w`

The `d` command in combination with a movement command deletes text. In this case, `d2w` means "delete to the beginning of the second next word."

### Example:

Suppose you have the following text:
```
This is a sample text to demonstrate vi commands.
```

- If the cursor is at the beginning (`T`), pressing `d2w` will delete `is a`.

So, after executing `d2w`, the text becomes:
```
This sample text to demonstrate vi commands.
```

These commands allow you to navigate and edit text efficiently in `vi` or `vim` by moving and deleting text based on word boundaries.

<br/>
<br/>
<br/>

**In `vim`, replacing text can be done using several commands and modes. Here are some common methods to replace text:**

### Replace Single Character

1. **Command Mode**:
   - Position the cursor over the character you want to replace.
   - Press `r` followed by the replacement character.

   Example:
   ```vim
   This is a text.
   ```
   Place the cursor over the `a`, then press `ra`.
   ```vim
   This is r text.
   ```

### Replace Multiple Characters

1. **Command Mode**:
   - Position the cursor at the beginning of the text you want to replace.
   - Press `c` followed by the movement command to specify the range of text to replace. Then press `Esc`.
   
   Example:
   ```vim
   This is a text.
   ```
   Place the cursor at the beginning of `text`, then press `ct.` and `Esc`.
   ```vim
   This is a sentence.
   ```

### Replace All Occurrences

1. **Command Mode**:
   - Use the substitute command `:%s/search/replace/g` to replace all occurrences of `search` with `replace` in the entire file.
   
   Example:
   ```vim
   :%s/text/word/g
   ```
   This will replace all occurrences of `text` with `word` in the entire file.

### Replace in a Range

1. **Command Mode**:
   - Specify a range before the substitute command to replace text within that range.
   
   Example:
   ```vim
   :10,20s/old/new/g
   ```
   This will replace all occurrences of `old` with `new` between lines 10 and 20.

### Confirm Before Replacing

1. **Command Mode**:
   - Use the substitute command with the `c` flag to confirm each replacement.
   
   Example:
   ```vim
   :%s/text/word/gc
   ```
   This will prompt for confirmation before replacing each occurrence of `text` with `word` in the entire file.

Remember, the `vim` editor provides powerful search and replace capabilities, allowing you to replace text efficiently based on your requirements.

<br/>
<br/>
<br/>
<br/>

# Piping in Linux
Piping in Linux refers to using the pipe (`|`) character to pass the output (stdout) of one command as input (stdin) to another command. This allows you to combine multiple commands to perform more complex operations.

### Example: `ls | grep DSA`

- **`ls`**: Lists the files and directories in the current directory.
- **`|`**: Pipe character to pass the output of `ls` as input to the next command.
- **`grep DSA`**: Searches for the string "DSA" in the input received from `ls`.

Here's how this command works step-by-step:

1. `ls` lists all files and directories in the current directory.
2. The output of `ls` is passed (piped) to `grep`.
3. `grep` searches for the string "DSA" in the input it receives from `ls`.
4. `grep` then displays the lines that contain the string "DSA".

### Example Output:

Suppose you have the following files in the current directory:

```
file1.txt
file2.DSA
file3.txt
```

When you run `ls | grep DSA`, the output will be:

```
file2.DSA
```

This is because `grep` filters the output of `ls`, showing only the lines containing the string "DSA".

### Additional Notes:

- You can chain multiple commands using pipes. For example:
  ```bash
  command1 | command2 | command3
  ```
  
- You can use pipes to redirect the output of a command to a file:
  ```bash
  ls | grep DSA > output.txt
  ```
  This will save the filtered output to a file named `output.txt`.

- Piping allows you to create powerful and efficient command-line workflows by combining the functionality of different commands.

<br/>
<br/>
<br/>
<br/>

## Dumping Logs into a Particular File

In Linux, you can redirect the output of a command to a file using the `>` operator. If the file already exists, it will be overwritten. To append the output to an existing file, you can use the `>>` operator.

#### Example: `ls > test.txt`

This command runs `ls` to list the files in the current directory and redirects the output to `test.txt`. If `test.txt` doesn't exist, it will create the file. If it already exists, it will overwrite its contents.

```bash
ls > test.txt
```

#### Example: `cat test.txt`

This command displays the contents of `test.txt` on the terminal.

```bash
cat test.txt
```

#### Example: `ls >> test.txt`

This command appends the output of `ls` to `test.txt`. If `test.txt` doesn't exist, it will create the file.

```bash
ls >> test.txt
```

## Use of `&&` in Linux

The `&&` operator is used to execute multiple commands sequentially, one after the other, only if the previous command succeeds (returns a zero exit status).

#### Example:

```bash
command1 && command2
```

In this example, `command2` will only be executed if `command1` succeeds (returns a zero exit status).

#### Practical Example:

```bash
mkdir test_directory && cd test_directory
```

- `mkdir test_directory`: Creates a new directory named `test_directory`.
- `cd test_directory`: Changes the current directory to `test_directory`.

In this example, `cd test_directory` will only be executed if `mkdir test_directory` succeeds, ensuring that you change to the new directory only if it has been successfully created.

<br/>
<br/>
<br/>
<br/>

# **`tar` Command**
The `tar` command is used in Linux and Unix-like operating systems for creating, viewing, extracting, and managing archive files. Let's break down the commands you provided:

### 1. `tar -cf archive.zip 1.txt 2.txt`

This command creates a new archive file named `archive.zip` containing `1.txt` and `2.txt`.

- `tar`: The tar command.
- `-cf`: Options for creating a new archive file.
  - `c`: Create a new archive.
  - `f`: Use the following filename for the archive.
- `archive.zip`: The name of the archive file to create.
- `1.txt 2.txt`: The files to include in the archive.

### 2. `tar -zcf archive.zip 1.txt 2.txt`

This command creates a compressed archive file named `archive.zip` containing `1.txt` and `2.txt` using gzip compression.

- `-z`: Compress the archive using gzip.
- `archive.zip`: The name of the compressed archive file to create.
- `1.txt 2.txt`: The files to include in the archive.

### 3. `tar -xvzf archive1.zip`

This command extracts the contents of the `archive1.zip` archive file while displaying verbose output (`-v`) and using gzip decompression (`-z`).

- `-x`: Extract files from an archive.
- `-v`: Display verbose output (list files as they are processed).
- `-z`: Use gzip decompression.
- `archive1.zip`: The name of the archive file to extract.

### 4. `tar xf archive1.zip -C folder_name`

This command extracts the contents of the `archive1.zip` archive file into a specific directory (`folder_name`).

- `-x`: Extract files from an archive.
- `-f`: Use the following filename for the archive.
- `archive1.zip`: The name of the archive file to extract.
- `-C folder_name`: Change to the specified directory before extracting.

### Summary:

- `tar -cf archive.zip 1.txt 2.txt`: Create an uncompressed archive.
- `tar -zcf archive.zip 1.txt 2.txt`: Create a compressed archive using gzip.
- `tar -xvzf archive1.zip`: Extract a gzip-compressed archive with verbose output.
- `tar xf archive1.zip -C folder_name`: Extract an archive into a specific directory.
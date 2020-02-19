# Vim Tutor

## **Navigation**

### 1:Basic Navigations
 - 'h', 'j', 'k', 'l' for arrow directions.
 - H, M, L for Highest point, Middle point & Lowest point in the viewpoint.


### 2:Windows Navigation with "Windows command mode"
 - Ctrl w + R - To rotate windows up/left.
 - Ctrl w + r - To rotate windows down/right.
 - Ctrl w + L - Move the current window to the "far right".
 - Ctrl w + H - Move the current window to the "far left".
 - Ctrl w + J - Move the current window to the "very bottom".
 - Ctrl w + K - Move the current window to the "very top".


## **Plugin Specific** 

### 1:Vundle Package Manager
 - Add the package name in ~/.vimrc
 - Open vim and type the command: > :PluginInstall 


### 2:2:Code Folding Plugin shortcuts
 - zc — close the fold (where your cursor is positioned)
 - zM — close all folds on current buffer
 - zo — open the fold (where your cursor is positioned)
 - zR — open all folds on current buffer
 - zj — cursor is moved to next fold
 - zk — cursor is moved to previous fold

### 3:fzf plugin shortcuts
 - :Files [PATH]    | Files (similar to  `:FZF` )
 - :GFiles [OPTS]   | Git files ( `git ls-files` )
 - :GFiles?         | Git files ( `git status` )
 - :Buffers         | Open buffers
 - :Colors          | Color schemes
 - :Ag [PATTERN]    | {ag}{6} search result ( `ALT-A`  to select all,  `ALT-D`  to deselect all)
 - :Rg [PATTERN]    | {rg}{7} search result ( `ALT-A`  to select all,  `ALT-D`  to deselect all)
 - :Lines [QUERY]   | Lines in loaded buffers
 - :BLines [QUERY]  | Lines in the current buffer
 - :Tags [QUERY]    | Tags in the project ( `ctags -R` )
 - :BTags [QUERY]   | Tags in the current buffer
 - :Marks           | Marks
 - :Windows         | Windows
 - :Locate PATTERN  |  `locate`  command output
 - :History         |  `v:oldfiles`  and open buffers
 - :History:        | Command history
 - :History/        | Search history
 - :Snippets        | Snippets ({UltiSnips}{8})
 - :Commits         | Git commits (requires {fugitive.vim}{9})
 - :BCommits        | Git commits for the current buffer
 - :Commands        | Commands
 - :Maps            | Normal mode mappings
 - :Helptags        | Help tags [1]
 - :Filetypes       | File types

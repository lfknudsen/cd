# Change-Dir

My override of `cd`, extracted from my [library of PowerShell cmdlets](https://gitlab.com/lfknudsen/pwsh)
because it may be of interest to people who don't want the full library.\
In my [$profile](https://gitlab.com/lfknudsen/pwsh-config), I have aliased `cd` to this script.

## Usage

#### It works as normal:
```
cd <location>
cd ..
cd ~
```

#### You don't need to escape whitespace:
`
cd destination path
`
is equivalent to
`
cd "destination path"
`

#### You can go back in history:
```
cd -
```

#### You can go forward in history:
```
cd +
```

#### You can go to the top-most root of the current directory:
```
cd ^
```

#### If you have my $profile, you can go to the initial directory:
```
cd =
```

## See also

My [config file](https://gitlab.com/lfknudsen/pwsh-config),
which in addition to enabling `cd =`, also has aliases for short-hands
`cd.., .., cd~, ~, cd-, -, cd+, +, cd^, ^, cd=, =`

My [full library of cmdlets](https://gitlab.com/lfknudsen/pwsh)

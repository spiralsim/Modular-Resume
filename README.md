# Modular Resume (spiralsim's Version)

# Key Features
This is an elegant, even more easy-to-use version of [@petezh's Modular Resume](https://github.com/petezh/Modular-Resume).

My version makes several additional improvements (at least for how I make my resumes):
1. Importing a list of components is simplified to just typing each component's ID.
2. Custom commands are available for frequent entry types: `\award`, `\experience`, and `\publication`.
3. The layout is even more dense, allowing more entries to be crammed in.
4. All colors are now black-and-white, making the resume look the same when printed.
5. The workflow works with plain LaTeX, no longer requiring LuaLaTeX.

# Examples
- [My default digital resume (sans-serif)](/resumes/engineering/Jeffrey_Tong_Resume.pdf)

# Quick Start
## Installation
Either use the Overleaf template directly or clone this repo and compile with TeX locally.

## Personalization
It should be pretty straightforward to just pattern-match exactly the components you need **if you have a decent understanding of LaTeX**. 

For some hints, here's a list of every file/folder you'll need to modify:
1. `/common.sty` starting from `\newenvironment{resume}`
2. Create a folder `/resumes/<resume name>/` for each resume you want to create (ex. `/resumes/general/`, `/resumes/research/`, `/resumes/teaching/`, etc.) You can do this quickly by making a copy of an existing resume folder.
3. `/entries/` and all subfolders should be filled with new a `.tex` file for each entry you'd like to add

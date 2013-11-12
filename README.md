# Boris's Author Tools

Collection of tools and scripts that help to write articles.

## What

### sh (shell scripts)

The shell scripts mostly represent shortcuts to common (TeX) text analysis via diction/style.
All scripts have the prefix **at-**, which makes it simple to use TAB completion to select the right one w/o having to remember individual script names.
Scripts that have the prefix **at-tex-** use detex to directly operate on TeX files.

* **CMakeLists.txt**: Use this to install the scripts via CMake
* **at-tex-diction**: Print wordy and commonly misused phrases in sentences
* **at-tex-style**: "Print all sentences in a document containing phrases that are either frequently misused or indicate wordiness"
* **at-tex-style-long**: Show long sentences (30 words or more)
* **at-tex-style-nominalizations**: Print all sentences containing nominalizations
* **at-tex-style-passive**: Print all sentences phrased in the passive voice
* **at-tex-worddist**: Show the word count in a document (e.g., to find words that are being used too often)

### js (HTML5/Javascript)

* **wordcount.html**: Character and word count (e.g., useful for rebuttals)
* **csv2tex.html**: Convert CSV tables to TeX tables (e.g., useful to quickly generate TeX tables out of spreadsheets)

## Author

B. Schauerte  
http://schauerte.me/

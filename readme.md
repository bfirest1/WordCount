## Description

Provides a real-time Word Count in the status-bar for Sublime Text 2. See: http://www.sublimetext.com/

Count words on document or in selections.

The minimal word length is 2 and does not count digits.

An estimated reading time is now appended to the end of the word count.

## Installation

Install this repository automatically via "Package Control" http://wbond.net/sublime_packages/package_control

## Preferences

 - `enable_live_count` : true 
 		
 		Allows to control if the live word counter is enabled. Otherwise will be enabled for selections only.

 - `enable_readtime` : true 
 		
 		Allows you to control if the estimated reading time is enabled.
 		Reading time is only displayed when there is a time > 1s.

## Inspiration

 - The main loop inspired by sublimelint https://github.com/lunixbochs/sublimelint
 - The count inspired by the original WordCount plugin http://code.google.com/p/sublime-text-community-packages/source/browse/#svn%2Ftrunk%2FWordCount committed by mindfiresoftware
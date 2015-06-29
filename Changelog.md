# Changelog #

## 2.3 2011-09-02 ##

  * Fixed scrolling issue introduced in Vim 7.3.
  * Check for terminal size changes more frequently.
  * Misc tagging cleanup.

## 2.2 2011-08-12 ##

  * Bugfixes. No new features.

## 2.1 2011-04-04 ##

  * Various performance improvements (Fast mode option)
  * Improved unicode handling
  * API additions (user-defined callback functions)
  * New key shortcuts (execute current file in Conque, etc...)
  * Bugfixes

## 2.0 2010-11-16 ##

  * Windows support added
  * Python 3 support added
  * Bugfixes

## 1.2 2010-10-10 ##

  * New API functions (BETA)
  * New ConqueTerm\_CloseOnEnd option
  * Bugfixes

## 1.1 2010-05-28 ##

  * Allow shell buffer to be hidden
  * Fix xterm colors
  * Allow custom key for leaving insert mode
  * Various other bugfixes

## 1.0 2010-02-03 ##

  * Complete python rewrite
  * Add support for ncurses based applications
  * Add continuous polling, instead of using `<Tab>`
  * Improve speed
  * Improve syntax highlighting

## 0.6 2009-12-18 ##

  * Fix GVim errors with non-english locale
  * No functional changes

## 0.5 2009-12-02 ##

  * Various performance enhancements and bugfixes.
  * Rewritten escape sequence processing

## 0.4 2009-10-30 ##

  * Improved history and tab completion
  * Fix escape sequence formatting and improve highlighting
  * Send selected text to shell from any buffer
  * Add special handling of "vi" and "man" commands
  * Various bugfixes

## 0.3 2009-10-14 ##

  * Apply escape sequence coloring to output, e.g. ls --color
  * Clean up syntax files for portability
  * Fix several Vim 7.1 bugs
  * Bugfixes for multiple shell buffers
  * Add experimental shell folding option

## 0.2 2009-10-02 ##

  * New subprocess management in Python instead of C
  * Stronger support in OS X and Windows
  * Faster/less buggy tab completion
  * Support for multiple shell buffers

## 0.1 2009-09-03 ##

  * Initial release
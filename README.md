eclipse_template
================

A template for an Eclipse workspace with preconfigured preferences.

Usage:
cp -r ~/workspace/[old-workspace]/.metadata/.plugins/org.eclipse.core.runtime/.settings ~/workspace/[new-workspace]/.metadata/.plugins/org.eclipse.core.runtime/

This won’t copy all your eclipse preferences for your workspace, but it will grab a majority of them. Once copied, you will have to review your own settings to see what got copied and what needs to be re-configured each time.

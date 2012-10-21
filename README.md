# Clean File Templates for Xcode 4

A set of bare bones Objective-C templates that include nothing but an `#import` appropriate for the base class, an `@interface` and an `@implementation`. Useful if you find yourself frequently deleting copyright headers and default method implementations.

### Installation

Create the user file templates directory if necessary and navigate to it:

    mkdir -p ~/Library/Developer/Xcode/Templates/File\ Templates && cd "$_"

Clone the repository into a directory of your choice. This directory will be used as the category name in Xcode.

    git clone https://github.com/mattstevens/xcode-clean-file-templates.git Clean

Xcode should automatically detect the new templates.

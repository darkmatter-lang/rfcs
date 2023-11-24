# RFC policy - the compiler

Where there is significant design work for the implementation of a language
feature, the preferred workflow is to submit two RFCs - one for the language
design and one for the implementation design. The implementation RFC may be
submitted later if there is scope for large changes to the language RFC.

## Changes which need an RFC

* New lints
* Large refactorings or redesigns of the compiler
* Changing the API presented to syntax extensions or other compiler plugins in
  non-trivial ways
* Adding, removing, or changing a stable compiler flag
* The implementation of new language features where there is significant change
  or addition to the compiler. There is obviously some room for interpretation
  about what constitutes a "significant" change and how much detail the
  implementation RFC needs.
* Any other change which causes backwards incompatible changes to stable
  behaviour of the compiler, language, or libraries


## Changes which don't need an RFC

* Bug fixes, improved error messages, etc.
* Minor refactoring/tidying up
* Implementing language features which have an accepted RFC, where the
  implementation does not significantly change the compiler or require
  significant new design work

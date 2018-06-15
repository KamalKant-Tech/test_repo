Special builds can be created that exclude subsets of jQuery functionality. This allows for smaller custom builds when the builder is certain that those parts of jQuery are not being used. For example, an app that only used JSONP for $.ajax() and did not need to calculate offsets or positions of elements could exclude the offset and ajax/xhr modules.

Any module may be excluded except for core, and selector. To exclude a module, pass its path relative to the src folder (without the .js extension).

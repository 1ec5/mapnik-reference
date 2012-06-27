## CHANGELOG

#### 2.2.2

* Fixed type definition of `font-directory` in reference targeting latest mapnik

#### 2.2.1

* Fixed type definition of `font-directory`, ensuring it is interpreted as a uri

#### 2.2.0

* Add `raster-composite-operation`

#### 2.1.0

* Add `invert()` image filter function
* Rename `color-spin` compositing to `colorize-alpha`

#### 2.0.0

* The style-property `image-filters` becomes of the `functions`
  type and gains `[name, arity]` specs for each function.

#### 1.0.0

* For the property `buffer-size` under the Map symbolizer,
  the CSS representation becomes `buffer-size`, not `buffer.

#### 0.0.1

* Added symbolizer-specific `composite-operation` code.
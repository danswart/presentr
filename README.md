
# presentr

<img src="inst/extdata/presentr-hexSticker-royalblue.png" width="25%" height="25%">
<img src="inst/extdata/presentr-hexSticker-gold.png" width="25%" height="25%">


embed_mp4 <- function(mp4_path, output_file = NULL) 

mp4_path = path to the MP4 video file (local file path or URL) as a character string.
output_file = optional output file path. If specified, the HTML video tag will be appended to this file.


Examples:

# Embed an MP4 video and print to console
embed_mp4("path/to/video.mp4")

# Append to a specific file
embed_mp4("path/to/video.mp4", "output.Rmd")

# Append to the default file (custom-output.rmd)
embed_mp4("path/to/video.mp4", "custom-output.rmd")

# Print to console for cut and paste 
embed_mp4("path/to/video.mp4")







presentr::find_duplicate_media()
presentr::get_media_calls()
presentr::lmt_gif_loops()
presentr::slides_to_bookdown()
presentr::transform_media_calls()
presentr::utils_pipe()
presentr::xtract_gifs_optional_save()
presentr::extract_imgs_optional_save()



## Installation

You can install the development version of presentr like so:

``` r
# FILL THIS IN! HOW CAN PEOPLE INSTALL YOUR DEV PACKAGE?
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r

library(presentr)

## basic example code

```

 <!-- badges: start -->
  [![Codecov test coverage](https://codecov.io/gh/danswart/presentr/branch/main/graph/badge.svg)](https://app.codecov.io/gh/danswart/presentr?branch=main)
  <!-- badges: end -->

## Code of Conduct


Please note that the presentr project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.

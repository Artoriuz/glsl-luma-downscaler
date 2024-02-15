# Luma Downscaler

## Overview
These shaders allow you to downsample the luma plane directly before it's merged with chroma and converted to RGB. This is only ever useful if you're using a luma doubler but outputting to a fractional scaling factor, or when you
really want to save resources when watching high-res content on a low-res display (4k content on a 1080p display is a good example).

I recommend using autoprofiles to only load these when they're actually useful.

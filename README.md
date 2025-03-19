# go-exif-remove

[![Go Reference](https://pkg.go.dev/badge/github.com/zitadel/exifremove.svg)](https://pkg.go.dev/github.com/zitadel/exifremove)
[![codecov](https://codecov.io/gh/zitadel/exifremove/graph/badge.svg?token=0Maqd3Crv0)](https://codecov.io/gh/zitadel/exifremove)

Removes EXIF information from JPG and PNG files

Uses [go-exif](https://github.com/dsoprea/go-exif) to extract EXIF information and overwrites the EXIF region.

```go
import 	"github.com/scottleedavis/go-exif-remove"

noExifBytes, err := exifremove.Remove(imageBytes)
```

See example usage in [exif-remove-tool](exif-remove-tool)


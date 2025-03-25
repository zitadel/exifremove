# go-exif-remove

[![Go Reference](https://pkg.go.dev/badge/github.com/zitadel/exifremove.svg)](https://pkg.go.dev/github.com/zitadel/exifremove)
[![codecov](https://codecov.io/gh/zitadel/exifremove/graph/badge.svg?token=0Maqd3Crv0)](https://codecov.io/gh/zitadel/exifremove)

Removes EXIF information from JPG and PNG files

Uses [go-exif](https://github.com/dsoprea/go-exif) to extract EXIF information and overwrites the EXIF region.

> [!NOTE]  
> This package was originally hosted at `github.com/scottleedavis/go-exif-remove` and got removed.
> In this repository we restored a copy out of the Go module cache and continued maintenance.

```go
import 	"github.com/zitadel/go-exif-remove"

noExifBytes, err := exifremove.Remove(imageBytes)
```

See example usage in [exif-remove-tool](exif-remove-tool)


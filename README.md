# encsync

Created after discussions in https://github.com/s3tools/s3cmd/issues/774.

Eventually I conceded and wrote my own tool for performing a client side encrypted s3 sync, with filename encryption, file size obfuscation, optional copy/move support (to prevent re-uploading on rename) and path flattening (so structure cannot be determined). I'm building the first prototype in Python for rapidly creating acceptance tests, and then it will be re-written in C.

It will be a month or so until it's ready for public consumption, but feel free to watch

This tool is being written for production usage so, despite the lack of maturity, you can take some comfort that the first release will have been battle tested before being opened to the public

# Node Crossdomain Proxy

[Node Crossdomain Proxy](https://github.com/premist/node-crossdomain-proxy) is extremely simple Node.js proxy. It just adds *Access-Control-Allow-Origin: ** for XHR. I used it for Windows Azure Storage Blob mirroring.

## Usage

Make request url like this:

http://`proxy url`/?src=`file you want to request`

**Note**: use file url without <code>http://</code>.


## Copyright

This code is licensed under **WTFPL license**. If you're tired with Windows Azure or something else - or if you're not - you can use my source freely, in any project. see [LICENSE](https://github.com/premist/node-crossdomain-proxy/blob/master/LICENSE) for more information.
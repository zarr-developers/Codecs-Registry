![image](https://user-images.githubusercontent.com/81817735/177476995-580fb2ed-0b4e-4bde-bfba-1fc70b044916.png)

# Registry (Zarr-Codecs)
## Created

2022-07-01
## Last Updated

2022-07-13
## Maintained By [Zarr-Developers](https://github.com/zarr-developers)

To know more about codecs, refer to this Research File

### [Link](https://alt-shivam.github.io/Codecs-Registry/Others/Research)
## Download this Registry
* [CSV](https://downgit.github.io/#/home?url=https://github.com/Alt-Shivam/Codecs-Registry/blob/main/Registry.csv)

## Registry

| **CodecID** | **CodecName** | **SourceCode** | **Type** | **Description** | **LastUpdate** |
|---|---|---|---|---|---|
| None | Checksum 32 |  | Numcodecs | Checksum Algorithm | 08/07/22 |
| None | Compat |  | Numcodecs |  | 08/07/22 |
| msgpack2 | MsgPack |  | Numcodecs | Codec to encode data as msgpacked bytes. Useful for encoding an array of Python | 08/07/22 |
| base64 | Base64 |  | Numcodecs | Codec providing base64 compression via the Python standard library. | 08/07/22 |
| categorize | Categorize |  | Numcodecs | Filter encoding categorical string data as integers. | 08/07/22 |
| delta | Delta |  | Numcodecs | Codec to encode data as the difference between adjacent values. | 08/07/22 |
| fixedscaleoffset | FixedScaleOffset |  | Numcodecs | Applies the transformation (x - offset) * scale to all chunks.  Results are rounded to the nearest integer | 08/07/22 |
| blosc | Blosc |  | Numcodecs |  | 08/07/22 |
| gzip | GZIP |  | Numcodecs | Codec providing gzip compression using zlib via the Python standard library. | 08/07/22 |
| bz2 | BZ2 |  | Numcodecs | Codec providing compression using bzip2 via the Python standard library. | 08/07/22 |
| lzma | LZMA |  | Numcodecs | Codec providing compression using lzma via the Python standard library. | 08/07/22 |
| lz4 | LZ4 |  | Numcodecs |  | 08/07/22 |
| zlib | Zlib (DEFLATE) |  | Numcodecs | Codec providing compression using zlib via the Python standard library. | 08/07/22 |
| zstd | ZStandard (ZSTD) |  | Numcodecs |  | 08/07/22 |
| packbits | PackBits |  | Numcodecs | Codec to pack elements of a boolean array into bits in a uint8 array. | 08/07/22 |
| pickle | Pickle |  | Numcodecs | Codec to encode data as as pickled bytes. Useful for encoding an array of Python string objects. | 08/07/22 |
| quantize | Quantize |  | Numcodecs | Lossy filter to reduce the precision of floating point data. | 08/07/22 |
| shuffle | Shuffle |  | Numcodecs | Codec providing shuffle | 08/07/22 |
| zfpy | ZFPY |  | Numcodecs | Codec providing compression using zfpy via the Python standard library. | 08/07/22 |
| astype | Astype |  | Numcodecs | Filter to convert data between different types. | 08/07/22 |
| bitround | Bitround |  | Numcodecs | Floating-point bit rounding codec | 08/07/22 |
| json2 | JSON |  | Numcodecs | Codec to encode data as JSON. Useful for encoding an array of Python objects. | 08/07/22 |
| None | AEC |  | ImageCodecs |  | 08/07/22 |
| None | APNG |  | ImageCodecs |  | 08/07/22 |
| None | AVIF |  | ImageCodecs |  | 08/07/22 |
| None | Brotli |  | ImageCodecs |  | 08/07/22 |
| None | Brunsli |  | ImageCodecs |  | 08/07/22 |
| None | Deflate64 / Enhanced Deflate |  | Others |  | 08/07/22 |
| None | Snappy |  | Others |  | 08/07/22 |
| None | LZS |  | Others |  | 08/07/22 |
| None | LZSS |  | Others |  | 08/07/22 |
| None | LZO |  | Others |  | 08/07/22 |
| None | LZFSE |  | Others |  | 08/07/22 |
| None | ZFP |  | Others |  | 08/07/22 |
| None | LZRW |  | Others |  | 08/07/22 |
| None | LZX |  | Others |  | 08/07/22 |
| None | LZWL |  | Others |  | 08/07/22 |
| None | LZ4HC |  | Others |  | 08/07/22 |
| None | LZW |  | Others |  | 08/07/22 |
| None | LZF |  | Others |  | 08/07/22 |
| None | GZIP |  | Others |  | 08/07/22 |

## Haven't found your codec listed here?
You can easily add your codec by following these simple steps. :tada:
### Steps to follow.
**Step.1**- Make sure you have the Codec related information in the following manner.
```
* Blosc
- A brief about how the compression technique works(2-3 lines)
- Where the codec is primarily used(webpages, PNGs, JPEGs, OS etc.)
- Comparing compression and decompression benchmarks/speeds
- Any other info you think is useful
- Important links for the codec(GitHub, Blog post, Implementations etc.)

```

**Step.2**- Clone and make changes to these project files.

* clone the repo.
```bash
git clone https://github.com/Alt-Shivam/Codecs-Registry.git
```

* Add your codec information in Registry.csv file.

* Make changes to README.md file of branch gh-pages.

**Step.3**- Push your changes to your forked repo and Generate a Pull Request.

### Thanks for Visiting!!!

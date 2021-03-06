# General

FFmpeg/FFprobe/Sox/Lame Lambda Layer for Amazon Linux 2 AMIs

Static build of FFmpeg/FFprobe, Sox & Lame for Amazon Linux 2, packaged as a Lambda layer.

Bundles:

- FFmpeg N-56320-ge937457b7b-static <https://johnvansickle.com/ffmpeg/>
- Sox v14.4.2 <http://sox.sourceforge.net>
- Lame 3.99.5 <http://lame.sf.net>

This application provides a, `LayerVersion`, which points to a
Lambda Layer ARN you can use with Lambda runtimes based on Amazon Linux 2 (such
as the `nodejs10.x` runtime).

# License

- FFmpeg: GPLv2.1 <http://ffmpeg.org/legal.html>, John Van Sickle's static build 20210225 GPL v3 <https://johnvansickle.com/ffmpeg/>
- Sox: GPLv2 <https://sourceforge.net/p/sox/code/ci/master/tree/LICENSE.GPL>, Static build <https://github.com/serverlesspub/sox-aws-lambda-binary/bin>
- Lame: LGPL <https://lame.sourceforge.io/index.php>, Static build <https://github.com/serverlesspub/sox-aws-lambda-binary/bin>

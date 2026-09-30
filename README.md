# pkg-rpm-audioreach-conf

RPM packaging for
[audioreach-conf](https://github.com/AudioReach/audioreach-conf) on
CentOS Stream 10 (aarch64).

audioreach-conf provides vendor-, chipset-, and board-specific configuration
data used by AudioReach components, including topology and calibration
key-value definitions for audio use cases. The Qualcomm (`--with-qcom`)
configuration set installs ACDB calibration data and card-definition XML files
for supported chipsets.

Supported chipsets in this build:

```text
qcm6490, qcs615, qcs8275, qcs8300, qcs9075, qcs9100, sm8750,
GLYMUR, Kaanapali, MAHUA, X1E80100
```

## License

This project is licensed under the BSD 3-Clause License.
See [LICENSE.txt](LICENSE.txt) for the complete license text.

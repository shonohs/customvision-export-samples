# Sample scripts for Custom Vision OpenVino models

| Task | Domain | Export Platform | Export Flavor | Link |
|------|--------|-----------------|---------------|------|
| Classification | General (compact) | OpenVino | null | [README](classification/README.md) |
| Classification | General (compact) | OpenVino | NoPostProcess | [README](classification/README.md) |
| Object Detection | General (compact) | OpenVino | null | [README](object_detection/README.md) |
| Object Detection | General (compact) [S1] | OpenVino | null | [README](object_detection/README.md) |
| Object Detection | General (compact) | OpenVino | NoPostProcess | [README](object_detection_no_postprocess/README.md) |
| Object Detection | General (compact) [S1] | OpenVino | NoPostProcess | [README](object_detection_no_postprocess_s1/README.md) |


# Set up
## Use Docker (Recommended)
```
docker build -t openvino .
```

## Install manually
Please follow OpenVino's [official document](https://docs.openvinotoolkit.org/latest/index.html) to install the OpenVino packages.
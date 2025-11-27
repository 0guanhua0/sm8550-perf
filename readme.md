# [spec](https://www.qualcomm.com/products/mobile/snapdragon/smartphones/snapdragon-8-series-mobile-platforms/snapdragon-8-gen-2-mobile-platform)

# [timm/mobilenetv4_conv_aa_large.e230_r448_in12k_ft_in1k](https://huggingface.co/timm/mobilenetv4_conv_aa_large.e230_r448_in12k_ft_in1k)

```
Params (M): 32.6
GMACs: 9.6 # 19.2 FLOPs
Activations (M): 43.9
```

# [perf](https://ai.google.dev/edge/litert/models/measurement#native_benchmark_binary_for_multiple_performance_options_in_a_single_run)

| mode                       | avg (ms) | GFLOPS |
|:--------------------------:|:--------:|:------:|
| gpu-fp16                   |   33.453 | 573.94 |
| gpu-default                |   60.079 | 319.58 |
| cpu w/ 4 threads (xnnpack) |  133.769 | 143.53 |
| cpu w/ 2 threads (xnnpack) |  207.961 |  92.33 |
| cpu w/ 4 threads           |  255.511 |  75.14 |
| cpu w/ 1 threads (xnnpack) |  274.609 |  69.92 |
| cpu w/ 1 threads           |  318.790 |  60.23 |
| nnapi (w/o accel name)     |  324.144 |  59.23 |
| cpu w/ 2 threads           |  386.475 |  49.68 |
| nnapi (nnapi-reference)    |  588.257 |  32.64 |

# AUR-python-onnxruntime-no-CUDA
these patches just comment out all the CUDA stuff and explicitly turn CUDA off in the build instructions

i don't have a CUDA-capable device, so without these changes, onnxruntime wouldn't work for me when OpenSeeFace tried to use it.
the way i've implemented them is messy. i don't know if there's a way to generalize them gracefully, but here's the patches for anybody who wants them!

# Understanding Tinygrad

debug_kernel_code.c is pretty cool.

To read:
https://developer.apple.com/documentation/metal/compute_passes/creating_threads_and_threadgroups
codegen utility

## Questions

Why is the zero grad attached to the optimizer?

- It seems that the optimizer keeps track of all of the gradients of a model.

Tensor.training = False #Check what this does

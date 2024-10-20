# centos-rt
preempt-rt patch for centos 3.10.0-123.9.2.el7

You can learn "how to apply preempt-rt patch to non-mainline kernel" from this patch.

CentOS kernel is significantly different from the mainline Linux in that it has new features in core part of the kernel. Core components usually have 5~10% more lines compared to the same version of mainline kernel.

It takes 3 weeks (full time) for me to make this patch.

Future work: I want to combine preempt-rt patch with litmus-rt.

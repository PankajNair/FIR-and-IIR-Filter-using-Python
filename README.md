# FIR and IIR Filter using Python
FIR (Finite Impulse Response) and IIR (Infinite Impulse Response) filters are two common types of digital filters used in signal processing. They are used to remove unwanted noise or signal components from a signal and can be used in a wide range of applications, including audio processing, image processing, and control systems.

FIR filters have a finite impulse response, meaning that their impulse response lasts for a finite number of samples. They are typically designed using a set of filter coefficients, which determine the shape and characteristics of the filter's frequency response. The filter coefficients are fixed, which means that the filter is stable and does not have feedback. FIR filters are known for their linear phase response, which means that the phase shift introduced by the filter is constant over all frequencies.

IIR filters, on the other hand, have an infinite impulse response, meaning that their impulse response lasts indefinitely. They are typically designed using a set of filter coefficients and feedback loops. The filter coefficients and feedback loops determine the shape and characteristics of the filter's frequency response. IIR filters are known for their nonlinear phase response, which means that the phase shift introduced by the filter varies with frequency.

FIR filters are generally preferred in applications that require a linear phase response, such as audio processing and digital communication systems. They are also less sensitive to coefficient quantization errors, making them easier to implement in hardware. IIR filters, on the other hand, are preferred in applications that require a more compact filter design and are less sensitive to filter order.

The filters were designed using the NumPy, MatPlotLib and SciPy libraries

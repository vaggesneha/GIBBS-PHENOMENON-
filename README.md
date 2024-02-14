# GIBBS-PHENOMENON

The Gibbs phenomenon is named after American physicist Josiah Willard Gibbs, who first described it in 1899. It is a fundamental limitation of the Fourier series approximation and can occur in many other areas of signal processing and analysis as well.

Gibbs phenomenon is a phenomenon that occurs in signal processing and Fourier analysis when approximating a discontinuous function using a series of Fourier coefficients. Specifically, it is the observation that the overshoots near the discontinuities of the approximated function do not decrease with increasing numbers of Fourier coefficients used in the approximation.

In other words, when a discontinuous function is approximated by its Fourier series, the resulting series will exhibit oscillations near the discontinuities that do not diminish as more terms are added to the series. This can lead to a “ringing” effect in the signal, where there are spurious oscillations near the discontinuity that can persist even when the number of Fourier coefficients used in the approximation is increased.

In mathematics, the Gibbs phenomenon is the oscillatory behavior of the Fourier series of a piecewise continuously differentiable periodic function around a jump discontinuity. The'N'th partial Fourier series of the function (formed by summing the 'N' lowest constituent sinusoids of the Fourier series of the function) produces large peaks around the jump which overshoot and undershoot the function values. As more sinusoids are used, this approximation error approaches a limit of about 9% of the jump, though the infinite Fourier series sum does eventually converge almost everywhere (pointwise convergence on continuous points) except points of discontinuity.

# quantlib_interp
QuantLib: Build a curve, observe the impact of interpolation method on swap rates

QuantLib is an awesome open-source library that provides quite a few useful out of the box functions. For example quickly building a yield curve and pricing basic payoffs. In this experiment:

- I build a yield curve from deposits, FRAs and swaps
- Tweak the curve point-wise and observe the influence of different interpolation methods


For example, below is the impact of tweaking each of the input rates (x-axis) on the 4.5Y swap rate.

<img src='interp.png'/>
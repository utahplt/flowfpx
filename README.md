FlowFPX
===

![FlowFPX: Nimble Tools for Debugging Floating-Point Exceptions](https://github.com/utahplt/flowfpx/blob/master/src/title.png)


FlowFPX is a toolkit for systematically debugging floating-point exceptions.

Components:

* `FloatTracker.jl` for logging and fuzzing exceptional values in Julia code:
  <https://github.com/utahplt/FloatTracker.jl>
  - Examples: <https://github.com/utahplt/FloatTrackerExamples>
* `Coalesced Stack-Trace Graphs` (CSTGs) for summarizing logs:
  <https://github.com/utahplt/CSTG>
* `GPU-FPX` for logging exceptions in NVIDIA GPU kernels:
  <https://github.com/LLNL/GPU-FPX>

Other Resources:

* JuliaCon 2023 talk recording:
  <https://www.youtube.com/live/rMrHCM1Etng?feature=share&t=10146>
* JuliaCon 2023 slides:
  <https://lambdaland.org/files/JuliaCon%202023%20FlowFPX.pdf>
* JuliaCon 2023 paper:
  <https://github.com/utahplt/juliacon2023-paper>
* Winter 2023 poster:
  <https://lambdaland.org/files/flowfpx_poster.pdf>



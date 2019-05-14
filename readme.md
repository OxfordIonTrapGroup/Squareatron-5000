Ultra-low noise limiting amplifier. Designed for stabilizing the amplitude of the RF voltages used in ion traps.

The circuit uses a low-noise digital circuit to convert an input "clock" to a square-wave with very stable amplitude. After band-pass filtering, we recover a sinusoid with stable amplitude.

Measurements using an R&S phase/amplitude noise meter demonstrate:
- No added phase noise compared with a top-of-the-range R&S synth
- AM noise limited by the measurement device at almost all offset frequencies (100k correlations). Broadband noise approximately at the -197dBc/Hz thermal noise floor!

Measurements with power detector show very low long-term drift. To do: post data

Currently, the output RF power is fixed at around 10dm depending on frequency. If desired, this could be made tunable either by adding a step attenuator at the output, or by using a DAC to trim the 3V3 supply voltage.
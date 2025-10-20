# ALSA UCM configuration for Chrome devices

Overlay of upstream alsa-ucm-conf

`ucm2` contains UCM configurations to overlay upstream

`overrides` contains UCM configurations that are modified from and replace upstream

# Upstreaming status

## Done
- acp3xalc5682m98
- acpd7219m98357
- acp3xalc5682101
- mt8183_da7219_r
- mt8183_mt6358_t

## WIP
- None currently

## Exists in upsteam but is missing features
- sof-glkda7219ma (DMIC Split)
- avs_da7219 (All AVS: support for all boards)
- avs_dmic
- avs_max98357a
- avs_max98373
- avs_max98927
- avs_nau8825
- avs_rt5514
- avs_rt5663
- avs_ssm4567
- hdaudioB0D2

## TODO
- sof-cmlda7219ma
- sof-cml_max9839
- sof-cml_rt1011_
- sof-cs42l42
- sof-da7219max98
- sof-glkrt5682ma
- sof-nau8825
- sof-rt5682
- sof-rt5682s-hs-
- sof-rt5682s-rt1
- sof-ssp_amp

## Will not be upstreamed
- sof-bxtda7219ma (SOF driver is not supported on upstream linux for APL platforms)

# Reminders For GDS

## Start Magic VLSI:

1. magic -T sky130A
2. def read src/tt_block_1x1_pg.def

## Write GDS Files

In magic GUI:
	File->Write GDS->gds/tt_um_noahgwood_qrng.gds

## Write LEF Files

In magic terminal:
	lef write lef/tt_um_noahgwood_qrng.lef

## ENABLE ACTIONS IN GITHUB

Keep actions disabled unless/until we need to build/validate, no sense in wasting compute time. 
To enable, go [here](https://github.com/NoahGWood/tt06-qrng/settings/actions) and set "Allow all actions and reusable workflows"
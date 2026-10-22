# tst-firmware-release

Factory images of the JetHome test-system firmware, one release per
firmware version. Each release holds `<name>-factory.bin` (flash at
offset 0x0), the doc `<name>.md` where there is one, and
`SHA256SUMS`. `<name>` is the board config, with the app appended
for a config named after the hardware only (for example
`jxd-pm380-e1eth-display-test`).

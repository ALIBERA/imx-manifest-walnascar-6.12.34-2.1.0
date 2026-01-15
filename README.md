# imx-manifest-walnascar-6.12.34-2.1.0

Frozen repo manifest for the NXP i.MX Yocto BSP.

---

## BSP information

- Original NXP manifest: `imx-6.12.34-2.1.0.xml`
- Branch: `imx-linux-walnascar`
- Linux kernel: 6.12.34
- NXP release: 2.1.0
- Yocto distribution: Walnascar

All projects are pinned to exact Git commit SHAs.

---

## How to use this manifest (students)

```bash
mkdir -p ~/imx-yocto-bsp
cd ~/imx-yocto-bsp

repo init -u https://github.com/ALIBERA/imx-manifest-walnascar-6.12.34-2.1.0 \
  -b main -m default.xml

repo sync -j$(nproc)

# pve-kernel

main:kernel 5.15.27
edge:kernel 5.17.1
## 自用pve-kernel 
- 修复了 NAT1 / FULLCONE-NAT 在 5.15/5.17 kernel上失效问题。  原项目：[@Chion82](https://github.com/Chion82/netfilter-full-cone-nat)
- linux kernel version :5.15.27-1  感谢：[@ubuntu-jammy](https://code.launchpad.net/~ubuntu-kernel/ubuntu/+source/linux/+git/jammy) [@pve-kernel](https://github.com/proxmox/pve-kernel)
- 添加ppp拨号组件
- 添加i225等驱动
- 开启了 io_uring+zerocopy支持
- 开启了NFT_FLOW_OFFLOAD 支持

## INSTALL
```
git clone https://github.com/sxx1314/pve-kernel
cd pve-kernel
dpkg -i *.deb
```

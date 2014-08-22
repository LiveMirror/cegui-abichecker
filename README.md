# CEGUI automatic ABI checker

1\. Make sure you have abi-compliance-checker
```bash
# as root
yum install abi-compliance-checker
```
2\. Call:
```bash
cd cegui-abichecker
./abi_checker --branch v0-8 abi_check
```
3\. Wait for it to finish
4\. Watch stdout, stderr
5\. Collect the bits in local-temp/output

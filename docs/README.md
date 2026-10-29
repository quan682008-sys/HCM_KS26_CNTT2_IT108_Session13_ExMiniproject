# GreenTech System – Phân hệ Quản lý Linh kiện & Trạm máy
**Cách chạy scripts:**
```Powershell
mkdir greentech-systems
cd .\greentech-systems\
cd .\scripts\
New-Item auto_report.bat
```

```CMD
cd greentech-systems
cd scripts
.\auto_report.bat
echo @echo off >> auto_report.bat 
echo echo === Bao cao chuyen nghiep === > auto_report.bat 
echo pause >> auto_report.bat
```
**Kiểm tra thiết bị**
- ✅ SSD Kingston NV2 500GB PCIe 4.0 NVMe M.2
- ✅ SSD Samsung 980 1TB PCIe 3.0 NVMe M.2
- ✅ SSD Kingston NV3 1TB PCIe 4.0 NVMe M.2
- ❎ SSD Crucial BX500 480GB 2.5-inch SATA III
- ❎ SSD Samsung 990 Pro 2TB PCIe 4.0 NVMe M.2

**Bảng thông số linh kiện**

Mã trạm	| Mã linh kiện | Thiết bị | Dung lượng | Cấu hình RAM trạm |
|:---:|:---:|:---:|:---:|:--:|
WS-01|LK-SSD-001|SSD Kingston NV2 500GB PCIe 4.0 NVMe M.2|500 GB|16 GB|
WS-02|LK-SSD-002|SSD Samsung 980 1TB PCIe 3.0 NVMe M.2|1 TB|32 GB|
WS-03|LK-SSD-003|SSD Kingston NV3 1TB PCIe 4.0 NVMe M.2|1 TB|32 GB|
WS-04|LK-SSD-004|SSD Crucial BX500 480GB 2.5-inch SATA III|480 GB|8 GB|
WS-05|LK-SSD-005|SSD Samsung 990 Pro 2TB PCIe 4.0 NVMe M.2|2 TB|64 GB|
# Obsidian Plugins Installation Guide

Hướng dẫn cài đặt 2 Obsidian plugins từ repository này.

## Requirements

Trước khi bắt đầu, hãy đảm bảo bạn đã có:

- [Git](https://git-scm.com/) đã được cài đặt
- [Obsidian](https://obsidian.md/) đã được cài đặt
- Một Obsidian Vault:
  - Có thể tạo mới một Vault
  - Hoặc sử dụng Vault hiện có

---

## Installation Steps

### 1. Clone repository

Mở terminal và chạy:

```bash
git clone https://github.com/hungpn23/obsidian-plugins.git
```

Sau khi clone thành công, bạn sẽ có thư mục:

```text
obsidian-plugins/
```

Bên trong chứa 2 plugin cần cài đặt.

---

### 2. Copy plugins vào Obsidian Vault

Mở thư mục repository vừa clone.

Copy **cả 2 folder plugin** bên trong:

```text
obsidian-plugins/
├── plugin-1/
└── plugin-2/
```

Sau đó paste vào thư mục:

```text
<Vault của bạn>/.obsidian/plugins/
```

Ví dụ:

```text
MyVault/
├── Notes/
├── Attachments/
└── .obsidian/
    └── plugins/
        ├── plugin-1/
        └── plugin-2/
```

> Lưu ý: thư mục `.obsidian` là thư mục ẩn. Nếu không thấy, hãy bật chế độ hiển thị hidden files trên hệ điều hành của bạn.

---

### 3. Enable plugins trong Obsidian

Mở Obsidian và làm theo các bước sau:

1. Vào:

```
Settings → Community plugins
```

2. Nếu Community plugins đang bị tắt:
   - Bật **Community plugins**

3. Nhấn nút:

```
Reload
```

(nút này nằm bên trái mục **Installed plugins**)

4. Tìm 2 plugins vừa cài đặt trong danh sách **Installed plugins**

5. Bật toggle để enable cả 2 plugins.

---

### 4. Restart Obsidian

Sau khi enable plugins:

1. Tắt hoàn toàn Obsidian
2. Mở lại Obsidian

Việc restart giúp đảm bảo plugins được load đầy đủ.

---

## Troubleshooting

### Plugin không xuất hiện trong Installed plugins

Kiểm tra:

- Folder plugin có nằm đúng vị trí không:

```text
<Vault>/.obsidian/plugins/<plugin-folder>
```

- Mỗi plugin phải chứa đầy đủ các file cần thiết, ví dụ:

```text
plugin-folder/
├── main.js
├── manifest.json
└── styles.css (optional)
```

- Đảm bảo bạn đã reload danh sách plugins trong Obsidian.

---

## Done 🎉

Sau khi hoàn thành các bước trên, cả 2 plugins đã được cài đặt và có thể sử dụng trong Obsidian Vault của bạn.

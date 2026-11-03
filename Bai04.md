


# Phần 1. Phân tích

| Incognito Mode | Dedicated Profile |
|---|---|
| Phiên tạm thời | Lưu trữ lâu dài |
| Xóa dữ liệu phiên khi đóng hết cửa sổ ẩn danh | Giữ dữ liệu trên ổ cứng |
| Không lưu lịch sử duyệt web | Lưu lịch sử, Cookie, Bookmark |
| Không phù hợp quản lý nhiều tài khoản lâu dài | Phù hợp tách biệt tài khoản |

**Giải pháp:** Tạo 3 Profile riêng để cách ly Cookie,
lịch sử và mật khẩu.

# Phần 2. Triển khai trên macOS

## Tạo 3 Chrome Profile

1. Mở Chrome → Nhấn biểu tượng hồ sơ.
2. Chọn Add Profile (Thêm hồ sơ).
3. Tạo 3 Profile:
   - Personal: Tài khoản cá nhân.
   - Work: Quản trị GreenLog.
   - Sandbox: Kiểm thử.

## Cây thư mục Bookmark

Bookmarks
├── Personal
│   └── Trang cá nhân
├── Work
│   ├── GitHub
│   └── Portal GreenLog
└── Sandbox
    └── Canvas LMS

## Cloud Sync

Đăng nhập tài khoản Google riêng cho từng Profile
→ Settings → You and Google → Sync
→ Bật đồng bộ Bookmarks.

Không đồng bộ mật khẩu hoặc dữ liệu cá nhân
sang Profile Work.

# Phần 3. Kiểm thử

Trên máy tính công cộng:

1. Mở Chrome → Guest Mode.
2. Không lưu mật khẩu hoặc bật Sync.
3. Đăng xuất website sau khi sử dụng.
4. Đóng toàn bộ cửa sổ Guest để xóa dữ liệu phiên.

**Kết luận:** Profile riêng giúp giảm xung đột phiên,
Guest Mode phù hợp khi dùng máy công cộng.



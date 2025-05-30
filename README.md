# Copy vào thư viện hệ thống
cp libhg.so.2.0.0 /usr/local/lib/
cp libmsquic.so.2 /usr/local/lib/

# Tạo symbolic links (nếu cần)
ln -sf /usr/local/lib/libhg.so.2.0.0 /usr/local/lib/libhg.so
ln -sf /usr/local/lib/libmsquic.so.2 /usr/local/lib/libmsquic.so

# Cập nhật cache thư viện
ldconfig

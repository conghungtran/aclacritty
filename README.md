# Tải về (ví dụ bản stable)
wget https://github.com/neovim/neovim/releases/download/stable/nvim-linux64.tar.gz

# Giải nén
tar -xzf nvim-linux64.tar.gz

# Di chuyển vào thư mục Neovim
cd nvim-linux64

# Copy các file vào hệ thống (cần quyền sudo)
sudo cp -r bin/* /usr/local/bin/
sudo cp -r lib/* /usr/local/lib/
sudo cp -r share/* /usr/local/share/

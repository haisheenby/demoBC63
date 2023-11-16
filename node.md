# Config git
git config --global user.name "..."
git config --global user.email "..."

# Khởi tạo repository ở local (máy tính)
git init -b main

# Kiểm tra thay đổi code
git status

# Đưa code thay đổi vào stage changes để chuẩn bị đưa lên remote repository
git add <tên file>

git add . (Đưa toàn bộ file đang thay đổi vào stage change)

git add -A (Đưa những file đã thay đổi, ngoại trừ vừa tạo mới vào stage change)

# add commit
git commit -m "nội dung commit"
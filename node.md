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

git add -A (Đưa tất cả file đã thay đổi vào stage change)

# add commit

git commit -m "nội dung commit"

## Lưu ý: chạy git add trước khi commit

# Connect local repo với remote repo

git remote add origin <link git repo>

# push code từ local repo lên remote repo

git push -u origin main (chỉ cần gõ đầy đủ ở lần push đầu tiên)

## Lưu ý : chạy lệnh git commit trước khi git push

git push

# git reset đưa file đang ở khu vực staged change => về lại khu vực changes
git reset . => đưa toàn bộ file đang ở stage change => change
git reset <tên file> => chỉ đưa file ở staged change => change

# branch
git branch => liệt kê branch đang có 

git branch <tên branch> => tạo 1 branch mới

git switch <tên branch> => chuyển qua branch <tên branch>

git checkout -b <tên branch> => tạo 1 branch mới và nhảy qua branch đó

git branch -m <tên branch mới> => đổi tên branch

git branch -D <tên branch> => xóa branch
=> đứng ở branch khác mới có thể xóa đc
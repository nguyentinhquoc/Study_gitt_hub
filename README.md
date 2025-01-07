# Lệnh cơ bản
Git add . (Thêm tất cả các file)
Git commit -m "your commit message" (Tạo một commit với thông điệp của bạn)
Git commit --amend (Gộp vào commit cuối cùng thay vì tạo commit mới)
git push -f (Đẩy thay đổi lên repository từ xa với tùy chọn force)

# Làm việc với remote
git remote add origin <url> (Thêm remote repository với tên 'origin')
git remote -v (Hiển thị các remote repository hiện có)
git fetch origin (Lấy dữ liệu mới nhất từ remote repository)
git pull origin main (Kéo dữ liệu mới nhất từ nhánh 'main' của remote repository)
git push origin main (Đẩy thay đổi lên nhánh 'main' của remote repository)

# Làm việc với branch
## mỗi nhánh tương ứng với 1 chức năng
git branch <branch-name> (Tạo một nhánh mới)
git checkout <branch-name> (Chuyển sang nhánh mới)
git merge <branch-name> (Gộp nhánh vào nhánh hiện tại)
git branch -d <branch-name> (Xóa nhánh sau khi đã gộp)
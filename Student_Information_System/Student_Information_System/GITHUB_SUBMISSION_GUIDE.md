# GitHub + LMS submission guide

## Project contents

- [ ] `main.py`, `sis/*.py`, `tests/test_system.py`, `requirements.txt`, run scripts.
- [ ] `data/students.txt`, `data/subjects.txt`, `data/enrollments.txt`, `data/grades.txt`, `data/settings.txt`. Active student/enrollment/grade files intentionally start empty.
- [ ] `sample_data/*.txt` fictional examples, plus sample subject records in `data/subjects.txt`.
- [ ] `README.md`, `DEMONSTRATION_GUIDE.md`, and `screenshots/*.png`.
- [ ] No actual student details, passwords, account hashes, tokens, or real private information. `data/users.txt` is initially empty and should NOT be uploaded. Git ignores it for CLI use, but browser uploads can still include manually selected files.

## Publish using the GitHub website (no Git commands required)

1. Sign in at https://github.com.
2. Open https://github.com/new.
3. Repository name: **Student-Information-System**. Choose **Public** (only if safe) and do not create a new README. Click **Create repository**.
4. Extract the ZIP file first. From the repository page, select **uploading an existing file**, or **Add file > Upload files**. Drag the project files and folders from the extracted `Student_Information_System` folder. **Do not upload the ZIP as your only file.**
5. Check that `data/users.txt` is NOT in the upload. If it appears, remove it from the upload. Verify that `main.py`, `sis/`, `sample_data/`, `screenshots/`, and `README.md` are included.
6. Commit changes. Inspect the repository root and open `README.md` and the screenshot folders to confirm they display correctly.

## Invite your instructor

1. Go to the repository > **Settings** > **Collaborators** (under Access) > **Add people**.
2. Enter **natzjun2@gmail.com** and select the appropriate GitHub account.
3. Send the invitation. The recipient must accept it to receive collaborator access.

## Video evidence: make the actual recordings yourself

See `DEMONSTRATION_GUIDE.md` for the outline, features to cover, and talking points. Demonstrate login, dashboard, student add/search/edit, subjects, enrollment, grade calculation, two reports, theme switching, staff restrictions, and inspect `.txt` storage and code. Never reveal passwords or personal records.

- Upload the video to **YouTube** (Public or Unlisted where people with the link can watch). Check that the instructor can watch it without signing into your account.
- Upload the video to **Facebook** with a visibility setting that lets the instructor view it (a private or friends-only post may be inaccessible). Test the video link.
- Save both direct video URLs.

## LMS links (replace placeholders with real links)

GitHub: https://github.com/YOUR_USERNAME/Student-Information-System
YouTube: PASTE_YOUR_YOUTUBE_VIDEO_LINK
Facebook: PASTE_YOUR_FACEBOOK_VIDEO_LINK

Do not submit placeholder links. Verify access using a logged-out/private browser window and ask the instructor to accept the GitHub invitation.

**This archive contains the local project only. No repository, videos, or collaborator invitation were created automatically.**

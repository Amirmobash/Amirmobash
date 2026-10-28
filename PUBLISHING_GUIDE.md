# Profile update — publishing guide / راهنمای انتشار

## What's included / محتویات

- `README.md`: shorter modern bilingual GitHub profile with project image cards.
- `PORTFOLIO_FULL.md`: the original README preserved without editing (plus a comment indicating preservation).
- `assets/*.svg`: original vector illustrations made for this profile, including the header and four project-specific visual cards.

**Actual project images:** the new README also links directly to the existing `lrox .PNG` in the `LROX-STEP` repository and `Braun.png` in `CableCarousel`. The other project thumbnails are **illustrations**, not photographs of the hardware.

## Installation via Git

1. Clone `https://github.com/Amirmobash/Amirmobash`.
2. Create a new branch before editing, e.g. `git switch -c profile-bilingual-visual-refresh`.
3. Copy `README.md`, `PORTFOLIO_FULL.md` and the complete `assets/` folder from this package into the repository root (replacing only `README.md`). Keep `index.html` unchanged.
4. Run:

```sh
git add README.md PORTFOLIO_FULL.md assets/
git commit -m "Redesign bilingual profile README with project visuals"
git push -u origin profile-bilingual-visual-refresh
```

5. Open a pull request into `main`, review the rendered README, then merge when satisfied.

## راهنمای فارسی

فایل اصلی README با نسخه جدید جایگزین می‌شود، اما متن کامل قبلی در `PORTFOLIO_FULL.md` باقی می‌ماند. برای ایمنی ابتدا یک Branch جدید ایجاد کنید، فایل‌ها را کپی کنید و سپس Pull Request بسازید. تصاویر SVG ساخته‌شده برای نمایش پروژه‌ها هستند؛ دو تصویر LROX و CableCarousel از فایل‌های موجود خود پروژه‌ها لینک شده‌اند.

> Note: The connected GitHub integration returned `403 Resource not accessible by integration` when creating a branch, so nothing was automatically uploaded or changed on GitHub.

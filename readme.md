<h1 align="center">💫 CosmicNvim</h1>

<p align="center">
<img alt="نسخه حداقلی Neovim" src="https://img.shields.io/badge/Neovim-0.11.0+-blueviolet.svg?style=flat-square&logo=Neovim&logoColor=white)](https://github.com/neovim/neovim">
<img alt="آخرین کامیت GitHub" src="https://img.shields.io/github/last-commit/CosmicNvim/CosmicNvim?style=flat-square&logo=Github">
<a href="https://discord.gg/EwdrKzVbvJ">
<img alt="دیسکورد" src="https://img.shields.io/discord/901609359291854899?style=flat-square&logo=Discord">
</a>
<a href="https://cosmicnvim.vercel.app/">
<img alt="وب‌سایت" src="https://img.shields.io/website?style=flat-square&up_message=live&label=website&url=https%3A%2F%2Fcosmicnvim.vercel.app%2F">
</a>
</p>

CosmicNvim یک پیکربندی Neovim سبک و خودرأی برای توسعه وب است که به طور خاص برای ارائه یک تجربه برنامه‌نویسی 💫 COSMIC طراحی شده است!

<img width="2531" alt="Screen Shot 2021-12-19 at 1 25 ۲۴ بعد از ظهر" src="https://user-images.githubusercontent.com/3721204/146691358-82a6ff64-1942-4351-ac53-e710a3e48700.png">

## 🚀 ویژگی‌های عالی

### LSP بومی

قابلیت LSP بومی با ویژگی‌های کامل!

- 📘 تعریف برو به
- 🔍 یافتن ارجاعات/نوع تعریف/اعلان
- 💡 اقدامات کد
- 🚨 تشخیص وضعیت خط
- 🔧 قالب‌بندی/لینت‌بندی به لطف [null-ls](https://github.com/jose-elias-alvarez/null-ls.nvim)

#### ویژگی‌های اضافی

- پنجره‌های تغییر نام سفارشی و اقدام کد از طریق [Cosmic-UI](https://github.com/CosmicNvim/cosmic-ui)
- قالب پیش‌فرض شگفت‌انگیز از طریق [tokyonight.nvim](https://github.com/folke/tokyonight.nvim)
- بهبود رابط کاربری از طریق [noice](https://github.com/folke/noice.nvim)
- هایلایت سینتکس بهبود یافته از طریق [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
- داشبورد از طریق [dashboard-nvim](https://github.com/glepnir/dashboard-nvim)
- خط وضعیت سفارشی از طریق [lualine](https://github.com/nvim-lualine/lualine.nvim)
- کاوش فایل‌ها از طریق [nvim-tree](https://github.com/kyazdani42/nvim-tree.lua)
- یابنده فازی از طریق [Telescope](https://github.com/nvim-telescope/telescope.nvim)
- ترمینال شناور با [toggleterm.nvim](https://github.com/akinsho/toggleterm.nvim)
- نصب خودکار LSP/formatter/linter از طریق [mason.nvim](https://github.com/williamboman/mason.nvim)
- تکمیل خودکار از طریق [nvim-cmp](https://github.com/hrsh7th/nvim-cmp)
- پشتیبانی از قطعه کد از طریق [LuaSnip](https://github.com/L3MON4D3/LuaSnip)
- مدیریت نشست از طریق [auto-session](https://github.com/rmagatti/auto-session)
- هایلایت سفارشی اضافی
- پنجره‌های شناور برای ارجاعات، تغییر نام، تشخیص، اقدامات کد و موارد دیگر!

_در حالی که CosmicNvim به طور خاص برای توسعه TypeScript/JavaScript طراحی شده است، باید بتواند تجربه‌ای عالی با هر زبان پشتیبانی شده توسط LSP ارائه دهد._

## 🛠 نصب

### راهنمای سریع

#### پیش‌نیازها

- Neovim (+0.11.0) nightly
- [Node.js](https://nodejs.org/en/)
- [prettierd](https://github.com/fsouza/prettierd)

#### نصب

```bash
# انتقال به دایرکتوری پیکربندی
cd ~/.config
# پشتیبان‌گیری از پیکربندی فعلی
cp -r nvim nvim.backup
# کلون کردن مخزن
git clone git@github.com:CosmicNvim/CosmicNvim.git nvim
# باز کردن nvim و نصب افزونه‌ها
nvim
```

به طور پیش‌فرض، فرض بر این است که دایرکتوری Cosmic git در `vim.fn.stdpath('config')` قرار دارد، یعنی `~/.config/nvim`.

اگر مخزن استخراج شده خود را به `~/.config/nvim` پیوند نمادین می‌دهید، باید متغیر محیطی shell ``COSMICNVIM_INSTALL_DIR` را که به نصب شما اشاره می‌کند، تعریف کنید.

نصب اضافی CosmicNvim [جزئیات](https://github.com/CosmicNvim/CosmicNvim/wiki/Installation).

نصب اضافی سرور LSP [جزئیات](https://github.com/CosmicNvim/CosmicNvim/wiki/Installing-LSP-servers).

حذف CosmicNvim [جزئیات](https://github.com/CosmicNvim/CosmicNvim/wiki/Uninstalling-CosmicNvim).

## 🎨 قالب‌بندی

_به‌زودی مستندات جدید منتشر می‌شود!_

## ⚙️ پیکربندی

[اطلاعات عمومی](./lua/cosmic/config/examples/readme.md)

[پیکربندی‌های Cosmic](./lua/cosmic/config/examples/config.lua)

[افزودن گزینه‌های بیشتر vim](./lua/cosmic/config/examples/editor.lua)

## ✨ دستورات Cosmic

### به‌روزرسانی CosmicNvim

CosmicNvim را به‌روز می‌کند آخرین نسخه

```دستور vim
:CosmicUpdate
```

## 🗺 نگاشت‌های پیش‌فرض

[پیمایش فایل](./lua/cosmic/plugins/telescope/init.lua)

[کاوشگر فایل](./lua/cosmic/plugins/nvim-tree/init.lua)

[ترمینال](./lua/cosmic/plugins/terminal/mappings.lua)

[LSP](./lua/cosmic/lsp/mappings.lua)

[سایر](./lua/cosmic/core/mappings.lua)

## 📷 تصاویر صفحه

[بیشتر ببینید](https://github.com/CosmicNvim/CosmicNvim/wiki/Screenshots)

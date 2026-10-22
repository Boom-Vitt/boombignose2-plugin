<!-- BBN:HEADER:START -->
<div align="center">

<img src=".github/brand/banner.svg" width="100%" alt="AI News Writer Plugin — Claude Code plugin to write AI/tech news in Thai or English" />

<a href="https://github.com/Boom-Vitt/boombignose2-plugin/stargazers"><img src="https://img.shields.io/github/stars/Boom-Vitt/boombignose2-plugin?style=flat-square&color=14b8a6&labelColor=0b1220" alt="stars" /></a>
<a href="https://github.com/Boom-Vitt/boombignose2-plugin/commits/main"><img src="https://img.shields.io/github/last-commit/Boom-Vitt/boombignose2-plugin?style=flat-square&color=14b8a6&labelColor=0b1220" alt="last commit" /></a>
<a href="https://github.com/Boom-Vitt"><img src="https://img.shields.io/badge/by-BoomBigNose-14b8a6?style=flat-square&labelColor=0b1220" alt="by BoomBigNose" /></a>

</div>
<!-- BBN:HEADER:END -->

# Boombignose Plugins

Claude Code **plugin marketplace** โดย **Boom-Vitt**

## ปลั๊กอินในมาร์เก็ตเพลส

| Plugin | คำอธิบาย |
| --- | --- |
| **ai-news-writer** | เขียนข่าว AI/เทคโนโลยีแบบมืออาชีพ โครงสร้างพีระมิดหัวกลับ รองรับไทย/อังกฤษ |

## ติดตั้ง

พิมพ์ในแชต Claude Code:

```
/plugin marketplace add Boom-Vitt/boombignose2-plugin
/plugin install ai-news-writer@boombignose-plugins
```

จากนั้นใช้งานได้เลย เช่น:

```
/ai-news OpenAI เปิดตัวโมเดลใหม่ --th --short
/ai-news https://example.com/press-release --en
```

หรือพิมพ์ขอเป็นภาษาธรรมดา เช่น "ช่วยเขียนข่าวเรื่อง… ให้หน่อย" แล้วสกิลจะทำงานอัตโนมัติ

## อัปเดต / ถอนการติดตั้ง

```
/plugin marketplace update boombignose-plugins
/plugin uninstall ai-news-writer@boombignose-plugins
```

## โครงสร้าง repo

```
.claude-plugin/marketplace.json     # แค็ตตาล็อกมาร์เก็ตเพลส
plugins/ai-news-writer/             # ตัวปลั๊กอิน
├── .claude-plugin/plugin.json
├── commands/ai-news.md             # /ai-news
└── skills/ai-news-writer/SKILL.md  # สกิลออโต้
```

## License
MIT © 2026 Boom-Vitt

<!-- BBN:FOOTER:START -->
---

<div align="center">

**สร้างโดย [BoomBigNose](https://github.com/Boom-Vitt)** · [Kruoop.com](https://kruoop.com) แหล่งเรียน AI + คอมมูนิตี้ · [Seeneo.ai](https://seeneo.ai) · [YouTube 220K](https://www.youtube.com/@BoomBigNose)

<sub>ถ้าโปรเจกต์นี้มีประโยชน์ กด ⭐ ให้กำลังใจกันได้เลย</sub>

</div>
<!-- BBN:FOOTER:END -->

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

# 🔧 Job&Talent Fork of data-diff

This is Job&Talent's maintained fork of [datafold/data-diff](https://github.com/datafold/data-diff) with critical fixes for our Redshift → BigQuery migration.

## 📦 Installation

```bash
pip install git+https://github.com/franpdyer-jt/data-diff.git@v1.0.0-jt1
```

**What's included in this fork:**
- ✅ Pydantic v2 compatibility (required for modern Python tooling)
- ✅ Redshift Spectrum external table schema query fixes
- ✅ Actively maintained for Job&Talent's data migration needs

**Other installation options:**
```bash
# Latest development version
pip install git+https://github.com/franpdyer-jt/data-diff.git

# Specific commit
pip install git+https://github.com/franpdyer-jt/data-diff.git@7aa11ea
```

**In requirements.txt:**
```txt
data-diff @ git+https://github.com/franpdyer-jt/data-diff.git@v1.0.0-jt1
```

---

### ⚠️ Upstream Status

As of May 17, 2024, Datafold is no longer actively supporting or developing open source data-diff. We're grateful to everyone who made contributions along the way. Please see [their blog post](https://www.datafold.com/blog/sunsetting-open-source-data-diff) for additional context on this decision.

Job&Talent maintains this fork to support our ongoing data migration work.

---

# data-diff: Compare datasets fast, within or across SQL databases

## Contributors

<a href="https://github.com/datafold/data-diff/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=datafold/data-diff" />
</a>

## License

This project is licensed under the terms of the [MIT License](https://github.com/datafold/data-diff/blob/master/LICENSE).

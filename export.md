```zsh
pandoc paper.md \
  --filter pandoc-crossref \
  --citeproc \
  --metadata-file=ref.yaml \
  -o paperout.docx \
  -w docx \
  --reference-doc=Assets/Manuscript_sbr.docx
```

需要安装pandoc-crossref

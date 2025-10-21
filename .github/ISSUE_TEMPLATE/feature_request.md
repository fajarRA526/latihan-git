---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: bug
assignees: fajarRA526

---

name: "💡 Feature Request"
description: Usulkan ide atau fitur baru untuk meningkatkan project ini.
title: "[Feature]: "
labels: ["enhancement"]
assignees: [NeilR12]

body:
  - type: markdown
    attributes:
      value: |
        Terima kasih sudah ingin berkontribusi 💪  
        Tolong isi detail usulan fitur kamu di bawah ini biar tim bisa meninjau dengan jelas.

  - type: input
    id: feature_summary
    attributes:
      label: "📝 Ringkasan Fitur"
      description: Jelaskan secara singkat fitur yang kamu usulkan.
      placeholder: "Contoh: Tambahkan dark mode di halaman utama."

  - type: textarea
    id: problem
    attributes:
      label: "🎯 Masalah yang Ingin Diselesaikan"
      description: Apa masalah atau kebutuhan pengguna yang mendorong ide ini?
      placeholder: "Contoh: Saat malam hari tampilan terlalu silau, jadi butuh dark mode."

  - type: textarea
    id: proposed_solution
    attributes:
      label: "🚀 Solusi atau Ide Fitur"
      description: Jelaskan ide atau solusi yang kamu pikirkan.
      placeholder: "Contoh: Tambahkan toggle switch di navbar untuk mengaktifkan dark mode."

  - type: textarea
    id: alternatives
    attributes:
      label: "🔄 Alternatif yang Pernah Dicoba"
      description: Apakah kamu sudah mencoba solusi lain sebelumnya?
      placeholder: "Contoh: Mengubah CSS manual di browser, tapi kurang efisien."

  - type: dropdown
    id: priority
    attributes:
      label: "📌 Prioritas Fitur"
      options:
        - Rendah
        - Sedang
        - Tinggi

  - type: textarea
    id: additional_notes
    attributes:
      label: "🗒️ Catatan Tambahan"
      description: Info lain yang bisa membantu memahami konteks fitur ini.
      placeholder: "Contoh: Dark mode bisa otomatis aktif sesuai waktu lokal."

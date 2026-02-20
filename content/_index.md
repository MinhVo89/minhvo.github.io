---
title: ""
summary: ""
date: 2022-10-24
type: landing

design:
  spacing: "5rem"

sections:
  # =========================
  # HERO (gọn như Eilidh)
  # =========================
  - block: resume-biography-3
    id: about
    content:
      username: me
      text: |-
        My research focuses on **translational MRI** for **neuro** and **cardiovascular** applications, with an emphasis on **quantitative imaging biomarkers** and **robust acquisition/analysis pipelines**.
      button:
        text: Download CV
        url: "uploads/resume.pdf"
      headings:
        about: ""
        education: ""
        interests: ""
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: lg
      avatar:
        size: large
        shape: circle

  # =========================
  # SELECTED MANUSCRIPTS (gọn)
  # =========================
  - block: markdown
    id: publications
    content:
      title: "Selected Manuscripts"
      text: |-
        *Equal contribution*

        1. **Hiroki Ohta***, **Nhat-Minh Van Vo***, Junichi Hata, Koshiro Terawaki, Takako Shirakawa, Hirotaka James Okano.  
           **“Utilizing Dynamic Phosphorous-31 Magnetic Resonance Spectroscopy for the Early Detection of Acute Compartment Syndrome: A Pilot Study on Rats.”**  
           *Diagnostics* (2020). DOI: **10.21203/rs.3.rs-143667/v1**
    design:
      columns: "1"

  # =========================
  # CONTACT (icons như hình bạn muốn)
  # =========================
  - block: markdown
    id: contact
    content:
      title: "CONTACT ME"
      text: |-
        <div style="display:flex;justify-content:center;gap:44px;align-items:center;flex-wrap:wrap;margin:18px 0 18px 0;">
          <a href="https://orcid.org/0000-0003-3306-5006" target="_blank" aria-label="ORCID" style="font-size:54px;color:inherit;text-decoration:none;">
            <i class="ai ai-orcid"></i>
          </a>

          <a href="https://scholar.google.com/citations?user=ImwA5u0AAAAJ&hl=vi" target="_blank" aria-label="Google Scholar" style="font-size:54px;color:inherit;text-decoration:none;">
            <i class="ai ai-google-scholar"></i>
          </a>

          <a href="https://github.com/MinhVo89" target="_blank" aria-label="GitHub" style="font-size:54px;color:inherit;text-decoration:none;">
            <i class="fab fa-github"></i>
          </a>

          <a href="mailto:minhvo89@gmail.com" aria-label="Email" style="font-size:54px;color:inherit;text-decoration:none;">
            <i class="fas fa-envelope"></i>
          </a>
        </div>

        <div style="display:flex;justify-content:center;margin-top:10px;">
          <a class="btn btn-primary btn-lg" href="/uploads/resume.pdf">DOWNLOAD CV</a>
        </div>
    design:
      columns: "1"
---

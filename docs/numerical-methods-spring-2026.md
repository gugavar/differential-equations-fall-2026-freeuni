from pathlib import Path

md = r"""# დიფერენციალური განტოლებები ინჟინრებისთვის

## რესურსები

- 📚 წიგნები:
  - [Fundamentals of Differential Equations and Boundary Value Problems — Nagle, Saff, Snider](https://drive.google.com/file/d/1AX-QjsPPABmDMrf4ZEogNRkWTxYo14f8/view?usp=share_link)
  - [Elementary Differential Equations and Boundary Value Problems — Boyce, DiPrima](https://drive.google.com/file/d/1fyQPTzGrD63WfCWoiJv1KeiekJI_K8a6/view?usp=share_link)
  - [Elementary Differential Equations with Boundary Value Problems — Edwards, Penney](https://drive.google.com/file/d/1whtP67nlNx3lp32u0nsnDaUxuKSv80pb/view?usp=share_link)
- 📄 [სილაბუსი](https://docs.google.com/document/d/1-iN1eAxiJ-IGniliN9Dq3ZKfRIjIicwr/edit?ouid=110148669605332798451&rtpof=true&sd=true&usp=sharing)
- 🧪 [MIT Mathlets](https://mathlets.org/mathlets/)
- 📚 [ფინალური გამოცდა](https://docs.google.com/document/d/1Kjx_Z24V12TaFEiiFi8YF6YbRBYTKSX3/edit?ouid=115006867327811336984&rtpof=true&sd=true&usp=drive_link)
- 📚 [წინა წლის ფინალური გამოცდა](https://drive.google.com/file/d/1vRMJkgkaoF9rCRFj45KvKSwYnbCps2mo/view?usp=drive_link)
- 📚 კიდევ ორი ფინალური წინა წლებიდან: [1](https://docs.google.com/document/d/1czmmmV0TaFST9fu_dyjcjoRcKqsgyPI5/edit?ouid=110148669605332798451&rtpof=true&sd=true&usp=drive_link); [2](https://docs.google.com/document/d/1lpA_uIRW-LIKAQ_0Lp-2QKCZJL3xnVfN/edit?ouid=110148669605332798451&rtpof=true&sd=true&usp=drive_link);

---

### ლექცია 29/30 — ფურიე მწკრივები

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1KNRQOIeabS3LMi262rVaYf7m1UWy9BE9/view?usp=drive_link)
- 📝 დავალება: წიგნიდან [3] წაიკითხეთ თავები 8.1, 8.2 და 8.4 — Fourier Series Methods.
  - თავი 8.1: 1, 3, 5, 9, 11, 13, 15, 17, 21, 23, 27, 28, 29, 31;
  - თავი 8.2: 1, 2, 3, 15, 17, 23;
  - თავი 8.4: 1, 3, 5, 7, 11, 18.

### ლექცია 27/28 — არა-ერთგვაროვანი წრფივი სისტემები

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1ga4onDbS693V4EBIAfT8GO2fVL1urMfY/view?usp=drive_link)
- 📝 დავალება: წიგნიდან [1] — Fundamentals of Differential Equations:
  - არა-ერთგვაროვანი წრფივი სისტემები: თავი 9.7, ნომრები: 7, 8, 9, 11, 13, 15, 17, 18, 20, 21, 22, 27, 32, 33, 34.

### ლექცია 25/26 — ერთგვაროვანი წრფივი სისტემები: რეალური და კომპლექსური ფესვების შემთხვევა

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1MPojqDHoVBjM0mJ_BVug1ULPx2TuOQGj/view?usp=drive_link)
- 📝 დავალება: წიგნიდან [1] — Fundamentals of Differential Equations:
  - წრფივი სისტემები: გვერდი 543: 1, 2, 3, 5, 6, 8, 14, 16, 19, 20, 21, 22;
  - ერთგვაროვანი წრფივი სისტემები: თავი 9.5, გვერდები 553–556, ნომრები: 1, 3, 5, 6, 7, 25, 26, 32, 33, 35, 36, 45, 46, 50;
  - კომპლექსური საკუთარი მნიშვნელობები: თავი 9.6, გვერდები 559–560, ნომრები: 1, 2, 10, 14, 19, 20, 21, 22.

### ლექცია 23/24 — კონვოლუცია და დელტა ფუნქცია

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1eZxSGiulFP3kkAMvokUkZJM_y0csFOJs/view?usp=drive_link)
- 📚 მეორე შუალედური გამოცდის ნიმუშები: [1](https://docs.google.com/document/d/1EFsMLUyz2hsjm235_l7dpXDE2E1nSkTG/edit?ouid=110148669605332798451&rtpof=true&sd=true&usp=drive_link); [2](https://docs.google.com/document/d/1vowqI7FAbyo3a6Ltom1Rijz6jKnd8ETV/edit?ouid=110148669605332798451&rtpof=true&sd=true&usp=drive_link);

### ლექცია 21/22 — იმპულსური მახასიათებელი, ტრანსფერ ფუნქცია

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1EGLWPlQHYVP_yHGhMLyhRIDFhxoFr_DM/view?usp=drive_link)
- 📝 დავალება: წიგნიდან [1] — Fundamentals of Differential Equations. ლაპლასის გარდაქმნა: თავები 7.8, 7.9, 7.10.
  - თავი 7.8: 3, 4, 29, 30, 31, 32;
  - თავი 7.9: 7, 9, 11, 18, 19, 20, 29, 30, 35;
  - თავი 7.10: 5, 10, 13, 15, 20, 21, 23, 24.

### ლექცია 19/20 — ლაპლასის გარდაქმნა და საწყის პირობებიანი ამოცანები

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1fu28ZRV7FB8Ecu00vzci_UNIUapTDrXp/view?usp=drive_link)
- 📝 დავალება: წიგნიდან [1] — Fundamentals of Differential Equations. ლაპლასის გარდაქმნა: თავები 7.3, 7.5, 7.6.
  - თავი 7.3: 1, 3, 5, 7, 9, 11, 13, 15, 29, 30;
  - თავი 7.5: 1, 3, 5, 7, 10, 13, 20, 21, 34;
  - თავი 7.6: 7, 8, 9, 11, 15, 18, 19, 20, 23, 25, 28, 33, 34, 35.

### ლექცია 17/18 — დიფერენციალური განტოლებების მწკრივებით ამოხსნა

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1sp8lF7prTfj9lCiaN_X6rpNDbKecIAKu/view?usp=drive_link)
- 📝 დავალება:
  - წიგნიდან [2] — Elementary Differential Equations — წაიკითხეთ თავები 5.1 და 5.2:
    - ხარისხობრივი მწკრივები: თავი 5.1, გვერდი 195: 2, 3, 4, 5, 7, 8, 9, 10, 12, 14, 19, 20, 21, 23;
    - დიფერენციალური განტოლების მწკრივებით ამოხსნა: თავი 5.2, გვერდი 204: 2, 4, 6, 8, 11, 12, 14;
  - n-ური რიგის განტოლებები, წიგნიდან [1] — წაიკითხეთ თავები 6.1 და 6.2:
    - n-ური რიგის დიფერენციალური განტოლებები: თავი 6.1, გვერდი 348: 16, 18, 19, 20, 22, 23;
    - n-ური რიგის ერთგვაროვანი დიფერენციალური განტოლებების ამოხსნა: თავი 6.2, გვერდი 354: 2, 6, 8, 10, 12, 16, 18, 20.
- 📚 წინა წლების მეორე შუალედური გამოცდები: [1](https://drive.google.com/file/d/1LKWN6vPDTkVgZWNDYkIzU7t8r5yM_7bU/view?usp=drive_link); [2](https://docs.google.com/document/d/1eMS39_Wq3zHAL7oYVflxcuWNnCVxxjSy/edit?ouid=110148669605332798451&rtpof=true&sd=true&usp=drive_link);

### ლექცია 15/16 — მეორე რიგის სისტემა: რხევები და ვიბრაციები. ოპერატორები და მაღალი რიგის დიფერენციალური განტოლებები

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1GLGo6_zZc6KseqqgXctQRfaHa3iS0boa/view?usp=drive_link)
- 🧪 [მეორე რიგის სისტემის ამპლიტუდა და ფაზა — demo](https://mathlets.org/mathlets/amplitude-and-phase-2nd-order/)
- 📝 დავალება: წიგნიდან [1] წაიკითხეთ თავები 4.9–4.10 და ამოხსენით:
  - თავისუფალი მექანიკური ვიბრაციები: თავი 4.9, გვერდები 242–243: 1, 2, 3, 4, 5, 7, 8, 9, 10, 14;
  - მექანიკური ვიბრაციები, ძალის შემთხვევა: თავი 4.10, გვერდი 250: 8, 9, 10, 11, 12, 13, 14, 16.

### ლექცია 13/14 — პარამეტრების ვარიაცია და მეორე რიგის სისტემები: სიხშირული, ამპლიტუდური და ფაზური მახასიათებლები

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1KWmrfZURXn4yKSjW1qitXOdpNxRBVPd2/view?usp=drive_link)
- 📝 დავალება: წიგნიდან [1] წაიკითხეთ თავი 4.6 და ამოხსენით:
  - პარამეტრების ვარიაცია: თავი 4.6, გვერდები 213–214, ნომრები: 1, 4, 7, 11, 20, 22, 23, 24, 25.
- 📚 კიდევ ორი წინა წლების შუალედური: [3](https://docs.google.com/document/d/1tw8goBdEvq9xFfr3jwOijWrNo25lADU-/edit?ouid=110148669605332798451&rtpof=true&sd=true&usp=drive_link); [4](https://docs.google.com/document/d/1PlEk_RifWf2qKjWHi5XMfWSvWNjfFH13/edit?ouid=110148669605332798451&rtpof=true&sd=true&usp=drive_link);

### ლექცია 11/12 — განმეორებადი და კომპლექსური ფესვების შემთხვევა და არა-ერთგვაროვანი განტოლებები

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1VP4ndN5E7MeFhsBjbHxsz7LubF3wPzES/view?usp=drive_link)
- 📝 დავალება: წიგნიდან [1] წაიკითხეთ თავები 4.3–4.5 და ამოხსენით:
  - მახასიათებელი განტოლების კომპლექსური ფესვების შემთხვევა: თავი 4.3, გვერდები 194–195: 9, 11, 17, 19, 23, 32, 34, 35;
  - განუსაზღვრელი კოეფიციენტების მეთოდი და სუპერპოზიციის პრინციპი: თავები 4.4–4.5, გვერდი 202: 1, 3, 5, 7, 9, 11, 13, 15, 17, 21, 25; გვერდები 207–208: 1, 2, 3, 5, 19, 21, 23, 43, 44, 45.

### ლექცია 9/10 — მეორე რიგის დიფერენციალური განტოლებები და რეალური ფესვების შემთხვევა

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1cHc1FATgo2x4VY8en1aYyjbi40sUvmla/view?usp=drive_link)
- 🧪 [მასა-ზამბარის სიმულაცია](https://gugavar.github.io/rand_resourses/single_mass_second_order_ode_demo_offline.html)
- 🧪 [მასა-ზამბარის სისტემა სინუსოიდური ინფუთით](https://mathlets.org/mathlets/amplitude-and-phase-2nd-order/)
- 📝 დავალება: წიგნიდან [1] წაიკითხეთ თავები 4.1–4.2 და ამოხსენით:
  - მასა-ზამბარის სისტემები და რხევები: თავი 4.1, გვერდები 178–179: 2, 3, 4, 5, 6, 7, 9;
  - მე-2 რიგის წრფივი ერთგვაროვანი განტოლებები: თავი 4.2, გვერდები 186–187: 3, 7, 9, 11, 17, 19, 20, 21, 23, 26, 29, 37, 39, 44.
- 📚 წინა წლების შუალედურები: [1](https://docs.google.com/document/d/1ZPvaXrymc65vyl_XfRTU0vyo4YHkpGnD/edit?ouid=110148669605332798451&rtpof=true&sd=true&usp=drive_link); [2](https://docs.google.com/document/d/1vV61v9lgegidfYfLR2vxvVOHpkED159_/edit?ouid=110148669605332798451&rtpof=true&sd=true&usp=drive_link);

### ლექცია 7/8 — კომპლექსური რიცხვები, გათბობა-გაგრილების სისტემები

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1usLVoNeLqBgUi9c66FexYOFVXaGalfQd/view?usp=drive_link)
- 🧪 [პირველი რიგის სისტემის ამპლიტუდა და ფაზა](https://mathlets.org/mathlets/amplitude-and-phase-1st-order/)
- 📝 დავალება: წიგნიდან [1] წაიკითხეთ თავები 3.1–3.5 და ამოხსენით:
  - გათბობა-გაგრილების ამოცანები: გვერდი 129, ნომრები: 3, 4, 5, 6, 9, 12, 13, 15, 16;
  - ნიუტონის მექანიკის ამოცანები: გვერდი 137, ნომრები: 7, 8, 13, 21, 24, 25;
  - წრედები: გვერდი 143, ნომრები: 1, 2, 3, 4, 5, 7, 8.

### ლექცია 5/6 — ზუსტი დიფერენციალური განტოლებები და მაინტეგრირებელი მამრავლის მეთოდი

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1YKZs3Slk0AQbgq_Cn5gAdqUc0wJTLsNO/view?usp=drive_link)
- 📝 დავალება: წიგნიდან [1] წაიკითხეთ თავები 2.4–2.5 და ამოხსენით:
  - ზუსტი დიფერენციალური განტოლებები: გვერდი 86, ნომრები: 2, 4, 6, 10, 12, 14, 15, 22, 24, 25, 28;
  - ზუსტი დიფერენციალური განტოლებების ამოხსნა მაინტეგრირებელი მამრავლის გამოყენებით: გვერდი 91, ნომრები: 1, 2, 3, 6, 8, 10, 12, 13, 14, 15, 16, 20.

### ლექცია 3/4 — განცალებად-ცვლადიანი და პირველი რიგის წრფივი დიფერენციალური განტოლებები

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1GuEQtD5s6K2NHvflD7EJjA-9onWyORn3/view?usp=drive_link)
- 📊 [სლაიდები](https://drive.google.com/file/d/1W8_E1q13oxpIycH6MH0kFEidxCNSIxXh/view?usp=share_link)
- 📝 დავალება: წიგნიდან [1] წაიკითხეთ თავები 2.1–2.3 და ამოხსენით:
  - განცალებად-ცვლადიანი განტოლებები: გვერდები 68–69, ნომრები: 1, 2, 3, 4, 7, 9, 11, 12, 15, 17, 20, 21, 25, 33, 35;
  - პირველი რიგის წრფივი დიფერენციალური განტოლებები: გვერდები 76–78, ნომრები: 7, 8, 11, 16, 19, 28, 30, 35, 36, 37.

### ლექცია 1/2 — დიფერენციალური განტოლებებით მოდელირების მაგალითები, საწყის პირობებიანი ამოცანები და მიმართულებითი ველები

- 🖥️ [ლექციის სქრინი](https://drive.google.com/file/d/1a6XQ_JKUEvsB845WWAEHCkmAESkXmKZY/view?usp=drive_link)
- 📊 [სლაიდები](https://drive.google.com/file/d/1-oQPhU4RgXeO4CouwVozvsjcJTRmcZlR/view?usp=drive_link)
- 🧪 [მიმართულებითი ველების დასახატი საიტი](https://homepages.bluffton.edu/~nesterd/apps/slopefields.html)
- 🧪 [ოილერის მეთოდის დემო](https://mathlets.org/mathlets/eulers-method/)
- 📝 დავალება: წიგნიდან [1]:
  - გვერდები 35–36, ნომრები: 2, 4, 5, 6, 8, 10, 12, 16, 20, 22;
  - გვერდები 43–44, ნომრები: 2, 4, 6, 7, 8, 12, 14, 18.
"""

path = Path("/mnt/data/differential-equations.md")
path.write_text(md, encoding="utf-8")

print(f"Created: {path}")
print(f"Characters: {len(md):,}")
print(f"Lines: {md.count(chr(10)) + 1}")

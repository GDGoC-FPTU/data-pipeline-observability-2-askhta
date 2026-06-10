# Experiment Report: Data Quality Impact on AI Agent

**Student ID:** 2A202600899
**Name:** Nguyen Hoang Lan
**Date:** 10/06/2026

---

## 1. Ket qua thi nghiem

| Scenario | Agent Response | Accuracy (1-10) | Notes |
|----------|----------------|-----------------|-------|
| Clean Data (`processed_data.csv`) | Agent tra loi dung san pham co gia tri cao nhat trong nhom Electronics | 9/10 | Du lieu sach, khong loi |
| Garbage Data (`garbage_data.csv`) | Agent bi anh huong boi gia tri bat thuong va du lieu sai dinh dang | 3/10 | Co outlier, null va duplicate |

---

## 2. Phan tich & nhan xet

### Tai sao Agent tra loi sai khi dung Garbage Data?

Garbage Data chua nhieu van de nhu duplicate records, gia tri am, gia tri rong, sai kieu du lieu va outlier. Khi Agent doc du lieu nay, cac gia tri bat thuong co the duoc xem la hop le va anh huong truc tiep den qua trinh suy luan. Vi du gia TV Premium = 999999999 co the lam Agent lua chon sai san pham. Du lieu rong hoac sai dinh dang cung co the gay loi trong qua trinh loc va tong hop thong tin. Dieu nay cho thay chat luong du lieu co tac dong rat lon den ket qua cua AI.

---

## 3. Ket luan

**Quality Data > Quality Prompt?**

Dong y.

Du prompt duoc viet rat tot, Agent van khong the dua ra cau tra loi chinh xac neu du lieu dau vao sai hoac khong day du. Chat luong du lieu la nen tang cua moi he thong AI va Data Pipeline.
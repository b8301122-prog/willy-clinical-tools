> 本章重點：用四等分法檢查視覺重心，透過字級、顏色濃度、面積三個槓桿調整平衡。

# 投影片排版:重心配置原則

> 書名:你的簡報就是比AI強:47個人類才懂的PPT技巧
> 章節:2-5 排版要注意「重心」的配置

---

## 核心概念

排版的「重心」不是物理重心,而是**視覺重心**。一張投影片的要素(文字、圖片、插畫、圖表)分布是否協調,決定了觀眾第一眼的感受。使用者在看到畫面的瞬間就會判斷「這個設計好不好」,而視覺協調度比實際內容更早影響這個判斷。

---

## 判斷重心的方法:輔助線

把投影片**平均分割成 4 等分**(加上縱向與橫向各一條輔助線),就能清楚看出要素集中在哪一區、哪裡留白過多。

```
┌─────────┬─────────┐
│    A    │    B    │
├─────────┼─────────┤
│    C    │    D    │
└─────────┴─────────┘
```

理想狀態:四個區塊的「視覺份量」大致平衡,重心落在正中央附近。

---

## 常見失衡類型

| 失衡類型 | 典型症狀 | 修正方向 |
|---|---|---|
| 左右失衡 | 要素擠在左側,右側(尤其右下)大片留白 | 以正中央為基準點,把要素往右移動,填滿右下區塊 |
| 上下失衡 | 內容偏上或偏下 | 往中央調整 |
| 大小不一致 | 文字、照片、插畫尺寸差異過大 | 統一量體,或用其他要素平衡 |

---

## 調整重心的三個槓桿

除了「移動位置」之外,可以操作這三個屬性來改變視覺份量(越大/越濃/越廣 → 越沉重):

1. **文字大小**:字級越大,重心越沉
2. **目標顏色**:顏色越濃(飽和度/對比度越高),重心越沉
3. **目標面積**:佔用面積越大,重心越沉

> 實務應用:如果某側要素太多搬不動,可以把對側要素**放大、加深顏色、或擴大色塊面積**來平衡。

---

## BEFORE / AFTER 案例要點

**BEFORE 的問題**:標題、內文、功能列表全部靠左,手機 mockup 也偏左,右下角大片空白 → 重心嚴重左偏。

**AFTER 的調整**:
- 刪掉一條次要的功能項(從 4 條變 3 條),避免左側過度擁擠
- 文字區與手機 mockup 整體往右移動
- 讓四個象限的視覺份量趨於平均

關鍵動作:**不是加東西填右邊,而是把既有要素往中央/右側推**。

---

## Checklist(可直接用於 prompt / skill)

建立或檢查投影片時,依序確認:

- [ ] 心中(或實際)畫出十字輔助線,把畫面分成 4 等分
- [ ] 四個象限的視覺份量是否大致平衡?
- [ ] 是否有某一側(特別是右下)出現不自然的大片留白?
- [ ] 若失衡,優先嘗試**移動要素**而非新增要素
- [ ] 移動仍無法平衡時,調整字級、顏色濃度、色塊面積三者之一
- [ ] 最終檢查:把畫面縮小到縮圖大小,瞇眼看整體是否穩定

---

## 可嵌入 prompt 的精簡版

```markdown
## Slide Layout Principle: Visual Center of Gravity

When designing or critiquing a slide, mentally divide it into 4 quadrants
with a vertical and horizontal guide line. Check whether visual weight is
balanced across quadrants.

Common failure: elements crowded on the left, large empty space on the
right (especially bottom-right) → left-heavy, feels unstable.

Fix priority:
1. Move existing elements toward center/right — do NOT add new elements
2. If still unbalanced, adjust one of: font size, color intensity,
   or element area on the lighter side
3. Rule of thumb: larger + darker + wider = heavier

Goal: visual weight centered, not necessarily geometric center.
```

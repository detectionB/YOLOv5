# YOLOv5 (AIHub Sample) - Team Repo

## Goal
AIHub Sample 데이터를 YOLOv5 학습 포맷으로 변환하고, Baseline(YOLOv5s)을 기준으로 추가 실험을 비교합니다.

## Team Agreement (Do not change)
- Class order fixed: `data/classes.txt` (48 classes)
- Train/Val split fixed (seed=42)
- BBox: COCO (x,y,w,h) -> YOLO normalized (xc,yc,w,h)
- Color + Gray 모두 사용

## Baseline Artifacts
- `results/baseline/results.png`
- `results/baseline/*curve.png`
- `results/baseline/confusion_matrix.png`
- `results/baseline/weights/best.pt`

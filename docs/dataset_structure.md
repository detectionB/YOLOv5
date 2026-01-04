# Dataset Structure (AIHub Sample)

## Original folder (Sample)
- 01.원천데이터/Color|Gray/위해물품|정보저장매체/클래스/세부폴더/이미지
- 02.라벨링데이터/Color|Gray/동일 구조 + COCO JSON

## Annotation format
- COCO JSON keys: images(list), annotations(list), categories(list), meta(list)
- images: id, file_name, width, height ...
- annotations: image_id, category_id, bbox[x,y,w,h] ...
- categories: id, name ...

## Stats (verified)
- Color images: 2501
- Gray images : 2501
- classes: 48

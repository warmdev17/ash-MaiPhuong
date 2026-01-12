# NỘP BÀI

## Tạo môn học mới

```
ash group create <tên môn học>
```

### Ví dụ

```
ash group create IT103A_MaiPhuong
```

## Tạo session mới

Cần đứng ở thư mục group ( môn học )

```
ash subgroup create <tên session>
```

### Ví dụ

```
ash subgroup create Session1
```

## Tạo project

Trường hợp 1: Tạo 1 project riêng lẻ

```
ash project create <tên project cần tạo>
```

Ví dụ:

```
ash project create HCM_KS25_CNTT4_HoangMaiPhuong_001
```

Trường hợp 2: Tạo nhiều project với tên giống nhau ( prefix )

```
ash project create -c <số lượng> -p <tên>
```

Ví dụ:

```
ash project create -c 5 -p Baitap
```

> **_OUTPUT_** 5 bài tập với tên Baitap1...Baitap5

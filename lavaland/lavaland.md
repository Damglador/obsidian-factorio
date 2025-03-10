
```math-tex

# Blue
blue = 0.5
blue_time = 10
blue_green = 20/blue_time
blue_red = 2/blue_time
blue_sulfur = 5/blue_time

# Red
red = 0 + blue*2
red_time = 6
red_plastic = 2/red_time
red_wire = 4/red_time
red_green = 2/red_time

# Green
green = 0 + red*2 + blue*20
green_time = 0.5
green_iron = 1/green_time
green_wire = 3/green_time

# Overall resources needed
iron = green_iron*green
wire = green_wire*green + red_wire*red
plastic = red_plastic*red

copper = wire/0.5

```

Зелені:
Виробництво 0,5с
Залізна пластина 1
Мідний дріт 3

Червоні:
Виробництво 6с
Пластмаса 2
Мідний дріт 4
Зелені 2

Сині:
Виробництво 10с
Зелені 20с
Червоні 2
кислота 5 од

ливарня жижі до ливарні плат 5 до 12 = 24 на 3,2 секунди 
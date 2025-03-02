
```math-tex

# Blue
blue = 20
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

синій конвеєр подає = 45 предметів/с
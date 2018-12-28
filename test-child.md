---
title: Child of Test
parent: Test
has_children: true
nav_order: 1

---
# Child of test

I am a child page.

Some context for child page.

    RoomTypes.all
    |> Enum.map(fn room_type ->
      IO.puts(room_type.title)
    end)

Some another content
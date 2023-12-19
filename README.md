# so-i-am-okay
i don't know
class Player:
    def __init__(self, name, health, money, vehicle):
        self.name = name
        self.health = health
        self.money = money
        self.vehicle = vehicle

    def display_info(self):
        print(f"Player: {self.name}")
        print(f"Health: {self.health}")
        print(f"Money: ${self.money}")
        print(f"Current Vehicle: {self.vehicle}")

# 示例用法
player1 = Player("Michael", 100, 100000, "Sports Car")
player1.display_info()

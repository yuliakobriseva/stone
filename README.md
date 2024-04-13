# stone
class Stone:
    def __init__(self, type, color, weight_grams):
        self.type = type
        self.color = color
        self.weight_grams = weight_grams

    def display_info(self):
        print("Stone Information:")
        print(f"Type: {self.type}")
        print(f"Color: {self.color}")
        print(f"Weight: {self.weight_grams} grams")

# Example usage
if __name__ == "__main__":
    # Creating an instance of the Stone class
    my_stone = Stone(type="Quartz", color="White", weight_grams=100)

    # Displaying information about the stone
    my_stone.display_info()

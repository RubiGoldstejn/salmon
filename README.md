# salmon
class Salmon:
    def __init__(self, species, length_cm, weight_kg, age_years):
        self.species = species
        self.length_cm = length_cm
        self.weight_kg = weight_kg
        self.age_years = age_years

    def display_info(self):
        print("Salmon Information:")
        print(f"Species: {self.species}")
        print(f"Length: {self.length_cm} cm")
        print(f"Weight: {self.weight_kg} kg")
        print(f"Age: {self.age_years} years")

# Example usage
if __name__ == "__main__":
    # Creating an instance of the Salmon class
    my_salmon = Salmon(species="Atlantic Salmon", length_cm=60, weight_kg=5, age_years=3)

    # Displaying information about the salmon
    my_salmon.display_info()

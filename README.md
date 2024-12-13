# Python_Day_19

def mad_libs():
    # Story template with placeholders
    story_template = (
        "Once upon a time in a {place}, there was a {adjective} {animal} named {name}. "
        "Every day, {name} would {verb} around the {place}, making everyone {emotion}. "
        "One day, {name} found a {adjective2} treasure that changed everything."
    )
    
    # Prompts for user inputs
    place = input("Enter a place: ")
    adjective = input("Enter an adjective: ")
    animal = input("Enter an animal: ")
    name = input("Enter a name: ")
    verb = input("Enter a verb: ")
    emotion = input("Enter an emotion: ")
    adjective2 = input("Enter another adjective: ")

    # Fill in the placeholders with user inputs
    story = story_template.format(
        place=place,
        adjective=adjective,
        animal=animal,
        name=name,
        verb=verb,
        emotion=emotion,
        adjective2=adjective2
    )

    # Display the final story
    print("\nHere's your Mad Libs story:\n")
    print(story)

# Run the Mad Libs generator
mad_libs()

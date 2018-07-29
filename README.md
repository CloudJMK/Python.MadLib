# Python.MadLib
"""
This program generates passages that are generated in mad-lib format
Author: CloudJMK 
"""

# The template for the story

print "The Mad Libs is starting!"
name = raw_input("Enter a name: ")
adj1 = raw_input("Enter an adjective: ")
adj2 = raw_input("Enter a second adjective: ")
animal = raw_input("Enter an animal: ")
food = raw_input("Enter a food: ")
verb1 = raw_input("Enter a verb: ")
noun1 = raw_input("Enter a noun: ")
fruit = raw_input("Enter a fruit: ")
adj3 = raw_input("Enter one more adjective: ")
name = raw_input("Enter a name: ")
superhero = raw_input("Enter a superhero: ")
country = raw_input("Enter a country: ")
name = raw_input("Enter a name: ")
dessert = raw_input("Enter a dessert: ")
name = raw_input("Enter a name: ")
year = raw_input("Enter a year: ")
noun2 = raw_input("Enter another noun: ")

STORY = "This morning %s woke up feeling %s. 'It is going to be a %s day!' Outside, a bunch of %s s were protesting to keep %s in stores. They began to %s to the rhythm of the %s, which made all the %s s very %s. Concerned, %s texted %s, who flew %s to %s and dropped %s in a puddle of frozen %s. %s woke up in the year %s, in a world where %s s ruled the world."

print STORY % (name, adj1, adj2, animal, food, verb1, noun1, fruit, adj3, name, superhero, name, country, name, dessert, name, year, noun2)

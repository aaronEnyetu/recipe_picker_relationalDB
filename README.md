# RandomRecipePicker

display random recipe using a GUI Tkinter application, SQLite3 and RecipeDB
<br>

<b>author:</b> Aaron Enyetu
<br>
<br>
<b> dependencies: </b>

- Tkinter
- Pillow (PIL)
- NumPy
- Pyglet (optional: used for Windows custom fonts)

<b>database webscraped from:</b>
<br>
<https://cosylab.iiitd.edu.in/recipedb/>
<br>
using MechanicalSoup and SQLite
<br>

recipes.db contains 2 tables:

- recipes (includes a primary_key column)
- ingredients (foreign key: recipe_key)

as a result, 2 functions were slightly modified:

- fetch_db()
- pre_process(recipe_name, table_records)



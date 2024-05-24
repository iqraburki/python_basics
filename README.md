
# # Task 1: Variables and Data Types

# In[1]:


age = 21 
name = "iqra burki" 
student = True  


# In[3]:


print("Age:", age)
print("Name:", name)
print("student:", student)


# In[4]:


new_age = age + 25
new_name = name + " Smith"
negated_student_status = not student


# In[5]:


print("New Age:", new_age)
print("New Name:", new_name)
print("Negated Student Status:", negated_student_status)


# # Task 2: String Manipulation

# In[10]:


sentence = "Python is a powerful programming language."
print(sentence)


# In[11]:


num_characters = len(sentence)
print("Number of characters in the sentence:", num_characters)


# In[12]:


sentence = "Python is a powerful programming language."
is_python_present = "Python" in sentence

print("Is 'Python' present in the sentence?", is_python_present)


# In[13]:


update_sentence = sentence.replace("powerful", "versatile")
print("Updated sentence:", update_sentence)


# In[14]:


words_list = sentence.split()

print("List of words:", words_list)


# ## Task 3: Expressions and Operators

# In[15]:


width = 5.5 
height = 3.25  
area = width * height

print("Area of the rectangle:", area, "square units")


# In[16]:


temperature_celsius = 25 
temperature_fahrenheit = (temperature_celsius * 9/5) + 32

print("Temperature in Fahrenheit:", temperature_fahrenheit, "°F")


# In[20]:


radius = 5  
pi = 3.14159
area = pi * (radius ** 2)

print("Area of the circle:", area, "square units")


# ## Task 4: Introduction to Data Structures
# 

# In[21]:


fruits = ["apple", "banana", "orange", "grape", "kiwi"]

print("List of fruits:", fruits)


# In[22]:


vegetables = ["carrot", "lettuce", "tomato", "broccoli", "spinach"]

print("List of vegetables:", vegetables)


# In[24]:


groceries = fruits + vegetables

print("Groceries: ", groceries)


# In[26]:


sorted_groceries = sorted(groceries)

print("Sorted groceries:", sorted_groceries)


# In[32]:


fruits.remove("banana")

print("Updated list of fruits:", fruits)


# ## Tuple

# In[38]:


colors = ("lilac", "green", "blue")

print("Tuple of colors:", colors)


# In[39]:


second_color = colors[1]

print("Second color in the tuple is:", second_color)


# In[40]:


months = ("January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December")
combined_tuple = months + colors
print("Combined tuple:", combined_tuple)


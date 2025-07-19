retrieved = Book.objects.get(title="1984")
print(retrieved.title, retrieved.author, retrieved.publication_year)
# Output: 1984 George Orwell 1949


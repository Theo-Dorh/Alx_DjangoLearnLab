from bookshelf.models import Book
Book.delete()
Book.objects.all()
# Output: <QuerySet []>

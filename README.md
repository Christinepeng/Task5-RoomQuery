# Task5-RoomQuery

Task: Create a Room database that has a table named `Book` with fields `id`, `title`, and `author`. Implement a DAO (Data Access Object) method that fetches all books written by a specific author.

Input Format: The `Book` table will have a primary key `id` of type `int`, a `title` of type `String`, and an `author` of type `String`.

Constraints: `id` is unique.
Both `title` and `author` fields have a maximum length of 100 characters.
Output Format: The DAO method should return a List of `Book` objects written by the specified author.

Entities
    User(id, name, email(no-verify), password)
    Note(id, name, creation_date, modified_date, created_by, hidden(bool), modified_by, permissions(sudo), content, owner(id) )
    Todo(id, description, reminder_date, status, hidden(bool), owner(id))

def check_password(password):
    if len(password) < 5:
        return "Password should be at least 5 characters long."
    if password[4].isdigit() or password[4] not in 'shetty777':
        return "Invalid password"
    return "Password is valid."

password = input("Enter your password: ")
result = check_password(password)
print(result)

for memeber, info in family_members.items():
    print(f"\nFamily Member: {memeber.title()}")
    name = f"{info['name']}"
    address = f"{info['address']}"
    number = f"{info['call']}"
    email = f"{info['email']}"

    print(f"\tFull Name: {name.title()}")
    print(f"\tAddress: {address}")
    print(f"\tPhone number: {number}")
    print(f"\tEmail: {email}")

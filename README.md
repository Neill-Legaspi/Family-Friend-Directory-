# Family-Friend-Directory-
# A directory storing important contact information for friends or family

# Prototype Dictionary

family_members = {
    'person_01': {
        'name': 'full name place holder',
        'address': 'Address place holder',
        'call': 'phone number place holder',
        'email': 'email place holder'
    },

    'person_02': {
        'name': 'full name place holder',
        'address': 'Address place holder',
        'call': 'phone number place holder',
        'email': 'email place holder'
    },

    'person_03': {
        'name': 'full name place holder',
        'address': 'Address place holder',
        'call': 'phone number place holder',
        'email': 'email place holder'
    },

    'person_04': {
        'name': 'full name place holder',
        'address': 'Address place holder',
        'call': 'phone number place holder',
        'email': 'email place holder'
    },

    'person_05': {
        'name': 'full name place holder',
        'address': 'Address place holder',
        'call': 'phone number place holder',
        'email': 'email place holder'
    },

    'person_06': {
        'name': 'full name place holder',
        'address': 'Address place holder',
        'call': 'phone number place holder',
        'email': 'email place holder'
    },

    'person_07': {
        'name': 'full name place holder',
        'address': 'Address place holder',
        'call': 'phone number place holder',
        'email': 'email place holder'
    },

}

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

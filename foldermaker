import os
def makeDirectories():
    while True:
        try:
            count = int(input("Enter the number of folders to create (1-5): "))
            if 1 <= count <= 13:
                break
            else:
                print("Please enter a number between 1 and 5.")
        except ValueError:
            print("Invalid input! Please enter a valid number (1-5).")

    for i in range(1, count + 1):
        folderName = f"Day {i}"
        try:
            os.mkdir(folderName)
            print(f"Folder created: {folderName}")
        except FileExistsError:
            print(f"Folder {folderName} already exists.")

makeDirectories()
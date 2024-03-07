# Welcome to CCDS2's Profile

Hey there! Welcome to my profile.

Here's a little interactive script to help you get to know me better:

```bash
#!/bin/bash

while true; do
    echo "Welcome!"
    echo "Please select an option:"
    echo "1. Show my name"
    echo "2. Show my interests"
    echo "3. Show what I'm currently learning"
    echo "4. Show what I'm looking to collaborate on"
    echo "5. Show how to reach me"
    echo "6. Show my pronouns"
    echo "7. Show a fun fact"
    echo "8. Exit"

    read -p "Select an option: " option

    case $option in
        1)
            echo "My name is @CCDS2"
            ;;
        2)
            echo "I'm interested in music/programming."
            ;;
        3)
            echo "Currently, I'm learning Java, but also Docker."
            ;;
        4)
            echo "If you ever want to collaborate on a project, feel free to reach out to me."
            ;;
        5)
            echo "You can reach me via Discord: #CDS2"
            ;;
        6)
            echo "My pronouns are: That/Guy"
            ;;
        7)
            echo "PowerShell syntax, it's trash :)"
            ;;
        8)
            echo "Goodbye!"
            exit 0
            ;;
        *)
            echo "Invalid option selected."
            ;;
    esac

    sleep 8
done


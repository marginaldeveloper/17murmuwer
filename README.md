def i_am_a_python_developer():
    experience = {
        "Programming": ["Python", "Django", "Aiogram (Telegram bots)", "SQLite3", "MySQL", "HTML", "CSS", 
                        "basic JavaScript", "Kivy", "Tkinter (GUI applications)"],
        "Tools": ["Git"],
        "Security_and_pentesting": ["OSINT (De-anonymization)", "Doxing", "Phishing attacks", 
                                    "Nmap/Acunetix/Nessus", "Metasploitable", "Aircrack", "Wifite", 
                                    "Hashcat", "Wireshark"],
        "Languages": ["Fluent in English", "Native Russian", "Basic German"],
        "Other_skills": ["Graphic design (Krita, Photoshop)"],
        "Databases": "I sell private databases related to 🇷🇺"
    }

    return experience

if __name__ == "__main__":
    my_skills = i_am_a_python_developer()
    print("As a Python developer, I have experience in:")
    for category, skills in my_skills.items():
        if isinstance(skills, list):
            print(f"- {category}: {', '.join(skills)}")
        else:
            print(f"- {category}: {skills}")

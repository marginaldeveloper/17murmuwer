#Hello, just a little drop of information about me
class PythonDeveloper:
    def __init__(self):
        self.skills = {

        
            "programming": [
                "Python 🐍",
                "Django 🌐",
                "Aiogram (Telegram bots) 🤖",
                "SQLite3 📊",
                "MySQL 🍔",
                "HTML 📜",
                "CSS 🎨",
                "JavaScript (basic) 💻",
                "Kivy 🌱",
                "Tkinter (GUI apps) 🖥️"
            ],

            
            "tools": [
                "Git 🛠️"
            ],
            "security": [
                "OSINT (De-anonymization) 🔍",
                "Doxing 📄",
                "Phishing attacks 🎣",
                "Nmap/Acunetix/Nessus 🛡️",
                "Metasploitable 💣",
                "Aircrack ☁️",
                "Wifite 📶",
                "Hashcat 🔑",
                "Wireshark 🌊"
            ],
        
            "languages": [
                "Fluent in English 🇬🇧",
                "Native Russian 🇷🇺",
                "Basic German 🇩🇪"
            ],
            
            "other_skills": [
                "Graphic design (Krita, Photoshop) 🎨",
                "Selling private databases related to 🇷🇺 💾"
            ]
        }

    def show_skills(self):
        for category, skills in self.skills.items():
            print(f"{category.capitalize()}:")
            for skill in skills:
                print(f" - {skill}")

if __name__ == "__main__":
    dev = PythonDeveloper()
    dev.show_skills()

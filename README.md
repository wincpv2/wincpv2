class Win:
    def __init__(self):
        self.name        = "Win"
        self.university  = "King Mongkut's University of Technology North Bangkok 🌾"
        self.major       = "Biomedical Engineering"
        self.also_knows  = "a little bit of everything 🧩"

        self.interests   = [
            "🫀  Medical Devices & Clinical Technology",
            "🤖  AI / Machine Learning",
            "🔬  Where biology meets code",
        ]

        self.currently   = "Exploring the space between medicine and AI"
        self.hidden_side = "Most of my real work happens in the lab, not here"
        self.fun_fact    = "I try so hard — and sometimes it works 💀"

    def say_hi(self):
        print("If you're curious about bio × tech, you're in the right place 🙌")

me = Win()
me.say_hi()

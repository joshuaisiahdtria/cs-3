class Glassware:
    def __init__(self,material):
        self.material = material
        
class Beaker(Glassware):
    def __init__(self, material):
        super().__init__(material)
        
class Tray:
    def __init__(self):
        self.beaker_1 = Beaker("glass")
        self.beaker_2 = Beaker("glass")
        self.beaker_3 = Beaker("glass")
        self.beaker_4 = Beaker("glass")
        self.beaker_5 = Beaker("glass")
        
def traycheck(var):
    if var in globals(): print("this tray has beakers.")
    else: print("the tray is missing, the glassware is lost.")

tray1 = Tray()
traycheck('tray1')

del tray1
traycheck('tray1')

# NexusRoute-The-Smart-Transit-Engine

class Stop:
    def __init__(self, stop_id, name, lat, lon):
        self.id = stop_id
        self.name = name
        self.lat = float(lat)
        self.lon = float(lon)

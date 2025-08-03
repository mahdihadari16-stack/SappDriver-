class SnappDriverApp(MDApp):
    def build(self):
        self.manager = ScreenManager()
        self.manager.add_widget(DriverPage(name="driver"))
        self.manager.add_widget(PassengerPage(name="passenger"))
        self.manager.add_widget(RideRequestPage(name="ride_request"))
        return self.manager

if __name__ == "__main__":
    SnappDriverApp().run()

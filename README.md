# remote-desktop-control

A websocket-based approach to control a desktop application through the web. More information and insights on the [related Medium post]().

## Try it yourself

Clone the repository and install the Python dependencies:

```bash
git clone git@github.com:frankie567/remote-desktop-control.git
cd remote-desktop-control
pip install -r requirements.txt
```

Start the server:

```bash
python server.py
```

Start the desktop app (where `client` is the identifier of this client):

```bash
python desktop.py client
```

Open `web.html` in your browser, type `client` (the same as the one you provided for the desktop) in the input field and click on *Connect*.

You now should see the CPU usage reported on the web page. If you click on *Beep*, the computer should make a sound.

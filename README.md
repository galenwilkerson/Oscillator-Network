# Oscillator Network Synchronization

## Two Coupled Oscillators

The file `two_oscillators.html` demonstrates two coupled oscillators vibrating slowly. Each oscillator is drawn as a circle, bobbing up and down according to its phase. Over time, the small coupling nudges them into synchronization, causing them to move in unison.

### How to Run

- **Live Demo**: [Click here](https://galenwilkerson.github.io/two_oscillators.html) to open the two-oscillator simulation directly in your browser.
- **Local**: Clone this repository, open `two_oscillators.html` in your browser, and click **Reset Phases** to watch them gradually synchronize.

---

## Larger Oscillator Network

The file `oscillator_network.html` demonstrates a larger network of oscillators that gradually synchronize. You can choose the number of oscillators and the connection probability, then watch the phases converge on the canvas.

### How to Run

- **Live Demo**: [Click here](https://galenwilkerson.github.io/oscillator_network.html) to open the multi-oscillator simulation in your browser.
- **Local**: Clone this repository, open `oscillator_network.html` in your browser, select parameters, and click **Initialize** to start.

### Features
- Random adjacency matrix with adjustable connection probability.
- Oscillators (nodes) placed in a circle, colored by phase.
- Kuramoto-like update rule in discrete time steps.
- Watch as the network synchronizes in real time.

Feel free to modify the parameters in the HTML code (e.g., time step `dt`, coupling strength) to explore different dynamics.

---

## Phase Cascade Demo

The file `phase_cascade_demo.html` allows you to click on any oscillator to instantly change its phase, creating a “kick” that propagates through the network. By observing how neighbors adjust, you can see the ripple of phase differences move through the system.

### How to Run

- **Live Demo**: [Click here](https://galenwilkerson.github.io/phase_cascade_demo.html) to open the phase-cascade simulation in your browser.
- **Local**: Clone this repository, open `phase_cascade_demo.html` in your browser, and click on any oscillator to give it a new random phase. Then watch the cascade unfold in real time.

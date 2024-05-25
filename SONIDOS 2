// Secuencias con sonidos

(
(
~sec1 = Pdef(\damp, Ppar([
	Pbind(\instrument, \tri,
	\dur, 1/4,
	\amp, Pseq(0.5, 0, 0, 0.5, 0.5, 0, 0.5, 0, 0, 0.5, 0.5, 0.5, 0.5, 0.5, 0.5, 0],inf),
	),
	Pbind(\instrument, \sine,
		\dur,1/8,
	\amp, Pseq([5, 0.5, 0, 0.5, 0.5, 0, 0, 0, 0, 0.5, 0.5, 0.5, 0.5, 0.5, 0.5, 0.5],inf),
	\out,10
	)
]))
);


(
~sec2 = Pdef(\room, Pbind(\instrument, \pulse,
	\dur, Pseq([0.5, 0.25, 0.25, 0.5], inf),
	\amp, Pseq([0.7, 0, 0.4, 0.6], inf),
	\freq, Pseq([440, 523.25, 659.26, 783.99], inf),
	\at, 0.01,
	\out,10
))
);
);

~sec1.play.quant(4);
~sec2.play.quant(4);



~sec1.stop;
~sec2.stop;


s.quit;

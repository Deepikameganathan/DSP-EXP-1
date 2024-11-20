# DSP-EXP-1
GENERATION OF ELEMENTARY DISCRETE - TIME SEQUENCES
PROGRAM:
clc;
clear all;
close all;
%UNIT IMPULSE SIGNAL%
N=8;
n=0;
x=ones(1,1);
subplot(3,3,1);
stem(n,x);
xlabel('n');
ylabel('x(n)');
title('UNIT IMPULSE SIGNAL');
%UNIT STEP SIGNAL%
N=8;
n=0:1:N-1;
x=ones(1,N);
subplot(3,3,2);
stem(n,x);
xlabel('n');
ylabel('x(n)');
title('UNIT STEP SIGNAL');
%UNIT RAMP SIGNAL%
N=8;
n=0:1:N-1;
x=0:1:N-1;
subplot(3,3,3);
stem(n,x);
xlabel('n');
ylabel('x(n)');
title('UNIT RAMP SIGNAL');
%EXPONENTIAL WAVE%
N=8;
n=0:1:N-1;
x=exp(n);
subplot(3,3,4);
stem(n,x );
xlabel('n');
ylabel('x(n)');
title('EXPONENTIAL WAVEFORM');
%SINE WAVE%
N=8;
n=0:1:N-1;
x=sin(.2*pi*n);
subplot(3,3,5);
stem(n,x);
xlabel('n');
ylabel('x(n)');
title('SINE WAVE');
%COSINE WAVE%
N=8;
n=0:1:N-1;
x=cos(.2*pi*n);
subplot(3,3,6);
stem(n,x);
xlabel('n');
ylabel('x(n)');
title('COSINE WAVE');

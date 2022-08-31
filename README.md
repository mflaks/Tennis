# Environment

## Goal
The goal of our agents is to keep the ball in play.

![tennis](tennis.JPG)

## Game Over
If an agent lets a ball hit the ground or hits the ball out of bounds

## Reward
In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.

## Actions
Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

## State
The observation space consists of 24 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation.

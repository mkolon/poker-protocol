# Tag-Team Poker Protocol

## Overview
The Tag-Team Poker Protocol (TTPP) allows for a poker game to accomodate from n + 1 to 2n players, where n is the number of sides or seats at the poker table. This is accomplished through a tag-team process where pairs of players work cooperatively to grow their stack of poker chips. TTPP keeps gameplay engaging for all participants and requires minimal central coordination (e.g., no timekeeping.)

## TTPP Pair Selection
TTPP pair selection is required whenever the number of poker players changes such that there are more players than seats.

A random selection process determines which players will participate in TTPP:
1. Each player is dealt a single card face up
2. The high card and low card form a TTPP pair
3. If additional TTPP pairs are required due to number of players and seats, continue forming pairs using the next highest and next lowest cards

## TTPP Pair Gameplay
The TTPP pair have a shared stack of poker chips. Each TTPP pair member is responsible for an equal buy-in share. The TTPP pair equally share any profits and losses over the course of their gameplay. It is left to the TTPP pair to coordinate and manage this cash-in and cash-out process themselves.

The TTPP pair member that received the lowest card during selection gets to sit at the table first and becomes the active player. The other TTPP pair member becomes the standby player.

TTPP pair gameplay then proceeds as follows:
1. The active player plays the poker hand while the standby player constructively observes (e.g., provides encouragement without opinion or recommendation - they are not the active player after all)
2. If the active player wins the hand (or is part of an equitably split pot) they remain the active player and TTPP pair gameplay begins again at step 1.
3. If the active player loses the hand the standby player becomes the active player and vice versa, and then TTPP pair gameplay begins again at step 1.
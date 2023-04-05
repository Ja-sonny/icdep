# Antiduplicate Method

## Remove duplicate with storage

We could write down all the receivers of the card on the card so that when giving the card, the person would know to whom the card can be passed to and to whom it cannot be passed to. This way, no one will receive the card twice. Additionally, even if someone makes a copy of the card, all the names will be copied as well. If there are no more receivers available since everyone has received the card the card will be thrown away

    This wouldn't work if the train is a - b - c - d - e
    and the b makes a copy of the card and gives it to c and d,
    and they decide to give each other the card. 

## Store the cards and make a copy to send out

Since the last method didn't work when there was a copy made, everyone in the
system could hold a copy of the card, so that they know that they have already
seen the card, and reject.

    Not so sure if works with the idea of the card only being 'received' once.
    Would it also be considered 'received' even if someone rejects to get 
    the card?

## Using a watermark or Making the card uncopiable 

This would only allow one card to be in the system, allowing all the members in the system to only receive the card once. We could make all the system to discard any cards that are going around without a watermark when they see one.

    Is is possible to make a card 'uncopiable' in the bit world?
    How would we create a Watermark so that it can be differentiated from all
    the fakes / copies
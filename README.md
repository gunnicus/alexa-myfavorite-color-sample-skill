# alexa-myfavorite-sample-skill
alexa invocation name - "sateesh favorite color"

## Intent schema
{
  "intents": [
    {
      "intent": "MyColorIsIntent",
      "slots": [
        {
          "name": "Color",
          "type": "LIST_OF_COLORS"
        }
      ]
    },
    {
      "intent": "WhatsMyColorIntent"
    },
    {
      "intent": "AMAZON.HelpIntent"
    },
    {
      "intent": "AMAZON.StopIntent"
    },
    {
      "intent": "AMAZON.CancelIntent"
    }
  ]
}

## Custom slots
  LIST_OF COLORS
      green
      red
      blue
      orange
      gold
      silver
      yellow
      black
      white
      
## Sample utterance
  WhatsMyColorIntent what's my favorite color
  WhatsMyColorIntent what is my favorite color
  WhatsMyColorIntent what's my color
  WhatsMyColorIntent what is my color
  WhatsMyColorIntent my color
  WhatsMyColorIntent my favorite color
  WhatsMyColorIntent get my color
  WhatsMyColorIntent get my favorite color
  WhatsMyColorIntent give me my favorite color
  WhatsMyColorIntent give me my color
  WhatsMyColorIntent what my color is
  WhatsMyColorIntent what my favorite color is
  WhatsMyColorIntent yes
  WhatsMyColorIntent yup
  WhatsMyColorIntent sure
  WhatsMyColorIntent yes please
  MyColorIsIntent my favorite color is {Color}
  AMAZON.HelpIntent help
  AMAZON.HelpIntent help me
  AMAZON.StopIntent stop
  AMAZON.StopIntent thanks goodbye
  AMAZON.CancelIntent cancel

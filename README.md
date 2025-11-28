# ReaLearn-NL3
ReaLearn Controller Compartment for the Nord Lead 3

This is a Controller Compartment for the Nord Lead 3 synthesizer to use with ReaLearn. The NL3 works nicely as a controller keyboard because it can display parameter changes on its LED rings. 

Import the following text into the controller department:

```json
{
  "kind": "ControllerCompartment",
  "version": "2.18.1",
  "value": {
    "defaultGroup": {},
    "groups": [
      {
        "id": "Bu1qwXi7snqVpC2bjHT7x",
        "name": "Control Section / Global"
      },
      {
        "id": "gQKGpTMMruenW6C-7x8GN",
        "name": "OSC 1"
      },
      {
        "id": "0PuuxiAiVM-sc6C1XoogH",
        "name": "OSC 2"
      },
      {
        "id": "YXHkH1MpwYehN8w0iPemf",
        "name": "AMP ENV"
      },
      {
        "id": "J9Ndc1vMLTmJmiTYhmwYw",
        "name": "FILTER ENV"
      },
      {
        "id": "qX1R5N37mkuuoRE0R8zz9",
        "name": "Filter Section"
      },
      {
        "id": "JlqhO8Nnq7Zp472icOGJv",
        "name": "LFO 1"
      },
      {
        "id": "Uw7O5FHxly6PAqc2KmVuq",
        "name": "LFO 2"
      },
      {
        "id": "sCHFKEYvnT_4x-f6qZeuz",
        "name": "MOD ENV"
      },
      {
        "id": "8dLA47YiFTHeJdlzcF0eo",
        "name": "OSC Mix & Mod"
      }
    ],
    "mappings": [
      {
        "id": "rX561bEDDxSneCqVMVgMi",
        "name": "Pitch Stick",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "type": 3,
          "channel": 0,
          "isRegistered": false,
          "is14Bit": false,
          "oscArgIndex": 0,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "type": 53,
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 58,
          "useProject": true,
          "moveView": true,
          "seekPlay": true,
          "oscArgIndex": 0,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "takeMappingSnapshot": {
            "kind": "LastLoaded"
          }
        }
      },
      {
        "id": "A_bhwyMBpXRWArOTOtygf",
        "name": "Modulation Wheel",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 1,
          "character": 2,
          "isRegistered": false,
          "is14Bit": false,
          "oscArgIndex": 0,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "type": 53,
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 56,
          "useProject": true,
          "moveView": true,
          "seekPlay": true,
          "oscArgIndex": 0,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "takeMappingSnapshot": {
            "kind": "LastLoaded"
          }
        }
      },
      {
        "id": "ujH7Iu35oMBFUrdnBLN77",
        "name": "Glide Rate",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 5,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 25,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "RV5AoyPs9Dfsf-QWPyKvg",
        "name": "OSC Mix",
        "groupId": "8dLA47YiFTHeJdlzcF0eo",
        "source": {
          "channel": 0,
          "number": 8,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 8,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "NLvlpsTOARmC21bUGl1dz",
        "name": "Mono toggle",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 15,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 2,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 4,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "Ghmopnc7u0GJg4kGddNzd",
        "name": "(Stereo) Unison toggle",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 16,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 2,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 6,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "N9YAoCjGFP2XblU-9pLTO",
        "name": "LFO 1 Rate Hz",
        "groupId": "JlqhO8Nnq7Zp472icOGJv",
        "source": {
          "channel": 0,
          "number": 19,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 29,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "GHq3XnC4b06j7LpxBi2gs",
        "name": "LFO 1 Waveform",
        "groupId": "JlqhO8Nnq7Zp472icOGJv",
        "source": {
          "channel": 0,
          "number": 20,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 12,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "n0FpPp1P2i_ZyGLt59Rlh",
        "name": "LFO 1 Destination",
        "groupId": "JlqhO8Nnq7Zp472icOGJv",
        "source": {
          "channel": 0,
          "number": 21,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 13,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "x6PBRdcbnzw2SEwJeTArI",
        "name": "LFO 1 Amount",
        "groupId": "JlqhO8Nnq7Zp472icOGJv",
        "source": {
          "channel": 0,
          "number": 22,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 31,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "fiLWrs9zTjBZPzA6NHTPj",
        "name": "LFO 2 Rate Hz",
        "groupId": "Uw7O5FHxly6PAqc2KmVuq",
        "source": {
          "channel": 0,
          "number": 23,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 32,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "rT0kbGb9A3_8Wdqxx9VkE",
        "name": "LFO 2 Destination",
        "groupId": "Uw7O5FHxly6PAqc2KmVuq",
        "source": {
          "channel": 0,
          "number": 24,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 15,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "Ki-EA69uC1IbQESKLNewE",
        "name": "LFO 2 Amount",
        "groupId": "Uw7O5FHxly6PAqc2KmVuq",
        "source": {
          "channel": 0,
          "number": 25,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 35,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "EcHvMMk5z8gnliZOUbwJ9",
        "name": "MOD ENV Attack",
        "groupId": "sCHFKEYvnT_4x-f6qZeuz",
        "source": {
          "channel": 0,
          "number": 26,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 37,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "VoJaVTspYz7jN8z4ZTPAk",
        "name": "MOD ENV Decay",
        "groupId": "sCHFKEYvnT_4x-f6qZeuz",
        "source": {
          "channel": 0,
          "number": 27,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 39,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "s5N7GvHv982QI0B_X_Wq0",
        "name": "MOD ENV Destination",
        "groupId": "sCHFKEYvnT_4x-f6qZeuz",
        "source": {
          "channel": 0,
          "number": 28,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 16,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "bK6vNYO6AZgeZZG8Rf73_",
        "name": "MOD ENV Amount",
        "groupId": "sCHFKEYvnT_4x-f6qZeuz",
        "source": {
          "channel": 0,
          "number": 29,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 41,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "MC3eLB3fUsmbPRgEJk1cE",
        "name": "OSC 1 Waveform",
        "groupId": "gQKGpTMMruenW6C-7x8GN",
        "source": {
          "channel": 0,
          "number": 30,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "outOfRangeBehavior": "ignore",
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 8,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "wo5PlSh_QkQ0oeNXOD-mh",
        "name": "OSC 2 Waveform",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 31,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 9,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "oVyOBwc4avnKYeHI2L3cI",
        "name": "Delete Navigator up",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 32,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "feedbackIsEnabled": false,
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "wau9Y4bo7GdV3HLWWbvup",
        "name": "OSC 2 Fine",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 33,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 4,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "7Tuz0sFTjMYM1xEiSh1OY",
        "name": "OSC 2 KBT toggle",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 34,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 2,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 23,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "R9A9elsEhhUj26GoK4ZB8",
        "name": "OSC 1 Sync/FM toggle",
        "groupId": "gQKGpTMMruenW6C-7x8GN",
        "source": {
          "channel": 0,
          "number": 35,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 21,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "hzlU93R6fQgXNHql26SmY",
        "name": "AMP ENV Decay",
        "groupId": "YXHkH1MpwYehN8w0iPemf",
        "source": {
          "channel": 0,
          "number": 36,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 10,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "4w90ja8gYnXsJGAqv4F0v",
        "name": "AMP ENV Sustain",
        "groupId": "YXHkH1MpwYehN8w0iPemf",
        "source": {
          "channel": 0,
          "number": 37,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 11,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "J3v1NqjQmoudd-duXziGQ",
        "name": "FILTER ENV Attack",
        "groupId": "J9Ndc1vMLTmJmiTYhmwYw",
        "source": {
          "channel": 0,
          "number": 38,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 14,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "kj44u934zRVIGRsvjqwtU",
        "name": "FILTER ENV Decay",
        "groupId": "J9Ndc1vMLTmJmiTYhmwYw",
        "source": {
          "channel": 0,
          "number": 39,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 16,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "pIFKJV8zIYVHRSDdNaOZ5",
        "name": "FILTER ENV Sustain",
        "groupId": "J9Ndc1vMLTmJmiTYhmwYw",
        "source": {
          "channel": 0,
          "number": 40,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 17,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "Jz7_NBthvbMvAWLA-buUY",
        "name": "FILTER ENV Release",
        "groupId": "J9Ndc1vMLTmJmiTYhmwYw",
        "source": {
          "channel": 0,
          "number": 41,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 18,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "An_48CzLkbEb0MtBbnRo_",
        "name": "FILTER 1 Resonance",
        "groupId": "qX1R5N37mkuuoRE0R8zz9",
        "source": {
          "channel": 0,
          "number": 42,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 21,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "RVJSQc_uvqlCp_50un3Yt",
        "name": "FILTER ENV Amount",
        "groupId": "J9Ndc1vMLTmJmiTYhmwYw",
        "source": {
          "channel": 0,
          "number": 43,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 19,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "cO4GI3t134giPUo4FP_LM",
        "name": "Filter type (Frequency1)",
        "groupId": "qX1R5N37mkuuoRE0R8zz9",
        "source": {
          "channel": 0,
          "number": 44,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxSourceValue": 0.4566929133858268,
          "minStepSize": 0.0,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 18,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "Mjhsb_ErDphPDgFJui7Dq",
        "name": "Filter type (Freq2/Dist)",
        "groupId": "qX1R5N37mkuuoRE0R8zz9",
        "source": {
          "channel": 0,
          "number": 44,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "minSourceValue": 0.5511811023622047,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 18,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "vhJKraRwwZCJgyLI4GArp",
        "name": "FILTER ENV Velocity",
        "groupId": "J9Ndc1vMLTmJmiTYhmwYw",
        "source": {
          "channel": 0,
          "number": 45,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 2,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 20,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "l8mg87TwH3ZJ-tFefOXE7",
        "name": "FILTER KB Tracking toggle",
        "groupId": "qX1R5N37mkuuoRE0R8zz9",
        "source": {
          "channel": 0,
          "number": 46,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 2,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 19,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "4b6yxPKIu3ojkvwPiMVbS",
        "name": "Arpeggiator run",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 47,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 2,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 1,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "24Qh82hkyISGtN-G3zpZO",
        "name": "Arpeggio Rate",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 50,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 24,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "o30Cljvzbv8Xg39YipEek",
        "name": "(Stereo) Unison Detune",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 53,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 26,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "CIebhM3EGft9EXYPxGBJV",
        "name": "Vibrato Rate",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 54,
          "isRegistered": false,
          "is14Bit": false,
          "oscArgIndex": 0,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "type": 53,
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 57,
          "useProject": true,
          "moveView": true,
          "seekPlay": true,
          "oscArgIndex": 0,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "takeMappingSnapshot": {
            "kind": "LastLoaded"
          }
        }
      },
      {
        "id": "M1Zot_2zWis_qOOcVyI6r",
        "name": "Delete? Scroll Pot / Preset Select",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 55,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "feedbackIsEnabled": false,
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "SI89NF30fmQEZkfghrKV1",
        "name": "Vibrato Source",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 56,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "minStepSize": 0.0,
          "maxStepSize": 0.0,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 2,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "ARazBVXmnNmrK35OvhTHc",
        "name": "FILTER 1 slope",
        "groupId": "qX1R5N37mkuuoRE0R8zz9",
        "source": {
          "channel": 0,
          "number": 58,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 17,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "bgYC4zSCakmO8so1_dm3x",
        "name": "FILTER Frequency2 (in Multi Mode)",
        "groupId": "qX1R5N37mkuuoRE0R8zz9",
        "source": {
          "channel": 0,
          "number": 59,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 55,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "PXTXruQPKm2sKvMnSeW-n",
        "name": "FILTER OSC 2  bypass toggle / Noise3 only",
        "groupId": "qX1R5N37mkuuoRE0R8zz9",
        "source": {
          "channel": 0,
          "number": 60,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 2,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 29,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "yzFrNHMA8HSzFB5_OuXEP",
        "name": "FILTER 2 Envelope Control (in Multi Mode) ",
        "groupId": "qX1R5N37mkuuoRE0R8zz9",
        "source": {
          "channel": 0,
          "number": 61,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 2,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 30,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "t3g0qQg2RrPT7kv7Q1MB3",
        "name": "FILTER ENV Amount Invert toggle",
        "groupId": "J9Ndc1vMLTmJmiTYhmwYw",
        "source": {
          "channel": 0,
          "number": 62,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 43,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "_NQ8jCEICeg3-Y1ghgKpe",
        "name": "FILT ENV Attack Type",
        "groupId": "J9Ndc1vMLTmJmiTYhmwYw",
        "source": {
          "channel": 0,
          "number": 63,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 15,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "zOYAwS2RfLKp7VAOVj4B9",
        "name": "Glide",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 65,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 3,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "16xwLfd64UR-zeS7zs8a2",
        "name": "OSC Mod Amount",
        "groupId": "8dLA47YiFTHeJdlzcF0eo",
        "source": {
          "channel": 0,
          "number": 70,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 7,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "vY_UO1fiD4rWGDnS4qIp0",
        "name": "AMP/Output Level",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 71,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 23,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "amKqFc5C7LuNMHJzU_vKp",
        "name": "AMP ENV Release",
        "groupId": "YXHkH1MpwYehN8w0iPemf",
        "source": {
          "channel": 0,
          "number": 72,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 12,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "O0VyVNoRZReiSn-qAGQyt",
        "name": "AMP ENV Attack",
        "groupId": "YXHkH1MpwYehN8w0iPemf",
        "source": {
          "channel": 0,
          "number": 73,
          "character": 2,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 9,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "H0dMS8o_BiR_p8hSE8qxX",
        "name": "FILTER 1 Cutoff",
        "groupId": "qX1R5N37mkuuoRE0R8zz9",
        "source": {
          "channel": 0,
          "number": 74,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 20,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "W0fEQvSWUwI2_HtvTvtcs",
        "name": "OSC 2 Coarse",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 78,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 6,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "Jv7QoZ19TQX-yhtfCM20d",
        "name": "OSC 1 Shape",
        "groupId": "gQKGpTMMruenW6C-7x8GN",
        "source": {
          "channel": 0,
          "number": 79,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 1,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "OGYgNULenVcnnORBS_oNE",
        "name": "LFO 1 Clock Sync toggle",
        "groupId": "JlqhO8Nnq7Zp472icOGJv",
        "source": {
          "channel": 0,
          "number": 81,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 27,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "eXRGM-VUPE5_uspT1voum",
        "name": "LFO 1 Env/KBS/Off",
        "groupId": "JlqhO8Nnq7Zp472icOGJv",
        "source": {
          "channel": 0,
          "number": 82,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 24,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "PSumzf2Atw2G1qro3quKJ",
        "name": "LFO 1 Mono mode toggle",
        "groupId": "JlqhO8Nnq7Zp472icOGJv",
        "source": {
          "channel": 0,
          "number": 83,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 25,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "Pfe5lmT7Y9bBuc4Phw6HJ",
        "name": "LFO 1 Amount Invert toggle",
        "groupId": "JlqhO8Nnq7Zp472icOGJv",
        "source": {
          "channel": 0,
          "number": 84,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 28,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "eOvgWO8pN0twSRuwuAWw7",
        "name": "LFO 2 Waveform",
        "groupId": "Uw7O5FHxly6PAqc2KmVuq",
        "source": {
          "channel": 0,
          "number": 85,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 14,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "RE_SDJrVR4fNETB07Vs3Z",
        "name": "LFO 2 Clock Sync toggle",
        "groupId": "Uw7O5FHxly6PAqc2KmVuq",
        "source": {
          "channel": 0,
          "number": 86,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 33,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "cuK11JI_iwg3hq3vdZ8ao",
        "name": "LFO 2 Env/KBS/Off",
        "groupId": "Uw7O5FHxly6PAqc2KmVuq",
        "source": {
          "channel": 0,
          "number": 87,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 26,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "mPNmR-iC2ry03hsTe05lj",
        "name": "LFO 2 Mono mode toggle",
        "groupId": "Uw7O5FHxly6PAqc2KmVuq",
        "source": {
          "channel": 0,
          "number": 88,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 2,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 27,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "tvxyUyLEP_I0jVFsni77Y",
        "name": "LFO 2 Amount Invert toggle",
        "groupId": "Uw7O5FHxly6PAqc2KmVuq",
        "source": {
          "channel": 0,
          "number": 89,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 36,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "C9bIv-kbT1NoC-WL7569q",
        "name": "OSC 2 Noise type (LP/BP/HP)",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 90,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 45,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "falwlNSjerwJpzRBrvD13",
        "name": "OSC 2 FM Amount (in Dual Sine FM)",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 93,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 46,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "nlAzxv4xWxFZhp1bRG8ad",
        "name": "Mono (Hi/Lo Note Priority)",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 94,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 31,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "kdrbx-vlE73ckfUNYbj1t",
        "name": "OSC 2 Dual Sine Carrier (in Dual Sine)",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 95,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 47,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "Nk9VcfhkvGaQ7qW_hQwce",
        "name": "OSC 2 Dual Sine Modulator (in Dual Sine))",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 96,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 48,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "KMedtQSB9zmZWHfWrI4X4",
        "name": "OSC 2 Noise Frequency",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 97,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 49,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "T5GtZH4DUsCyP5Wa4pA42",
        "name": "LFO 1 Clock Divisor BPM",
        "groupId": "JlqhO8Nnq7Zp472icOGJv",
        "source": {
          "channel": 0,
          "number": 99,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 30,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "Q1PMCMhjoPxN1_hgYsIwR",
        "name": "LFO 2 Clock Divisor BPM",
        "groupId": "Uw7O5FHxly6PAqc2KmVuq",
        "source": {
          "channel": 0,
          "number": 100,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 34,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "XcP812OWGRoXR2vZ0ao2S",
        "name": "MOD ENV Attack type",
        "groupId": "sCHFKEYvnT_4x-f6qZeuz",
        "source": {
          "channel": 0,
          "number": 101,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 38,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "NX3ua5OOQ8SE0RIdeqcsb",
        "name": "OSC 2 Shape",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 102,
          "character": 2,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 3,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "gWH1RpAyR0a2MlBfdmmgE",
        "name": "OSC 2 Sync/FM toggle",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 103,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 2,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 22,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "EqqE2V1f_MHFQcGsN7nyB",
        "name": "OSC 2 Partial On/Off",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 104,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 50,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "ED-JJopKwaaOtnUbhx7jt",
        "name": "Oscillator Modulation Type",
        "groupId": "8dLA47YiFTHeJdlzcF0eo",
        "source": {
          "channel": 0,
          "number": 105,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 11,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "zgk-OogFnex8ifpWSzYR-",
        "name": "OSC Mod Noise",
        "groupId": "8dLA47YiFTHeJdlzcF0eo",
        "source": {
          "channel": 0,
          "number": 106,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 44,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "DN-BCQ_AvRc3681BQiqYS",
        "name": "Oscillator Modulation Noise (not found)",
        "groupId": "8dLA47YiFTHeJdlzcF0eo",
        "source": {
          "number": 106,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 54,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "NCPZ7vRdu-FHqONV_5pZV",
        "name": "AMP ENV Attack Type",
        "groupId": "YXHkH1MpwYehN8w0iPemf",
        "source": {
          "channel": 0,
          "number": 107,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 13,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "H2QFMMXKC-U7OcnJFsume",
        "name": "MOD ENV Invert",
        "groupId": "sCHFKEYvnT_4x-f6qZeuz",
        "source": {
          "channel": 0,
          "number": 108,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 42,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "A8qN5N11maRnXlEAsaDPD",
        "name": "MOD ENV Release toggle",
        "groupId": "sCHFKEYvnT_4x-f6qZeuz",
        "source": {
          "channel": 0,
          "number": 109,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 40,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "YkGt_KbaI6wljfKRKgyc1",
        "name": "MOD ENV Repeat toggle ",
        "groupId": "sCHFKEYvnT_4x-f6qZeuz",
        "source": {
          "channel": 0,
          "number": 110,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 2,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 28,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "JpeNrkuMLZ2z5cXGxO_wp",
        "name": "Legato toggle",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 111,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 2,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 5,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "N1FK9ixrJwpnKG1SkNV7M",
        "name": "Chord Memory",
        "groupId": "Bu1qwXi7snqVpC2bjHT7x",
        "source": {
          "channel": 0,
          "number": 112,
          "character": 1,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "type": 1,
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 1,
          "rotateIsEnabled": true
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementType": "Button",
          "controlElementIndex": 7,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "o0C9kxXHBwY7WKcwBGYze",
        "name": "FILTER Distortion (in LP Dist mode only)",
        "groupId": "qX1R5N37mkuuoRE0R8zz9",
        "source": {
          "channel": 0,
          "number": 114,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 22,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "qFDY0DgoP7b4NkKLHdKb6",
        "name": "OSC 1 Sync Detune",
        "groupId": "gQKGpTMMruenW6C-7x8GN",
        "source": {
          "channel": 0,
          "number": 115,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 53,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "Fwx_jYPiSCfEpUnUql4M2",
        "name": "OSC 2 Sync Detune",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 116,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 5,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "_fun7vRZZQvFbsh9hIddx",
        "name": "OSC 1 Sync Noise Timbre ",
        "groupId": "gQKGpTMMruenW6C-7x8GN",
        "source": {
          "channel": 0,
          "number": 117,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 2,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "nJOpJOCiLPvukZxcIwsIG",
        "name": "OSC 2 Sync Noise Timbre",
        "groupId": "0PuuxiAiVM-sc6C1XoogH",
        "source": {
          "channel": 0,
          "number": 118,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 51,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      },
      {
        "id": "3cv3xZ0NAtN3LKYY-jBT3",
        "name": "OSC 1 FM Amount (in Dual Sine FM)",
        "groupId": "gQKGpTMMruenW6C-7x8GN",
        "source": {
          "channel": 0,
          "number": 119,
          "is14Bit": false,
          "buttonIndex": 0,
          "buttonDesign": {
            "background": {
              "kind": "Color"
            },
            "foreground": {
              "kind": "None"
            },
            "static_text": ""
          }
        },
        "mode": {
          "maxStepSize": 0.05,
          "minStepFactor": 1,
          "maxStepFactor": 5
        },
        "target": {
          "category": "virtual",
          "fxAnchor": "id",
          "useSelectionGanging": false,
          "useTrackGrouping": false,
          "seekBehavior": "Immediate",
          "controlElementIndex": 52,
          "mouseAction": {
            "kind": "MoveTo",
            "axis": "X"
          },
          "pollForFeedback": false,
          "takeMappingSnapshot": {
            "kind": "ById",
            "id": ""
          }
        },
        "advanced": {
          "on_activate": {
            "send_midi_feedback": []
          },
          "on_deactivate": {
            "send_midi_feedback": []
          }
        }
      }
    ]
  }
}
```

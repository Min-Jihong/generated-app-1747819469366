# Design Guidelines

{
  "design_guidelines": {
    "color_system": {
      "primary": "#6200EE",
      "secondary": "#03DAC6",
      "accent": "#FFDE03",
      "success": "#4CAF50",
      "error": "#F44336",
      "warning": "#FFC107",
      "background": "#FFFFFF",
      "surface": "#F5F5F5",
      "text_colors": {
        "primary": "#212121",
        "secondary": "#757575",
        "on_primary": "#FFFFFF"
      }
    },
    "typography": {
      "font_families": {
        "primary": "'Roboto', sans-serif",
        "secondary": "'Montserrat', sans-serif"
      },
      "font_sizes": {
        "body": "16px",
        "h1": "24px",
        "h2": "20px",
        "caption": "12px"
      },
      "line_heights": {
        "body": "1.5",
        "headings": "1.25"
      },
      "font_weights": {
        "normal": "400",
        "medium": "500",
        "bold": "700"
      }
    },
    "spacing": {
      "margin_padding_scale": "8px",
      "grid_system": "12 columns",
      "component_spacing": "16px"
    },
    "components": {
      "button_styles": {
        "primary": {
          "background_color": "#6200EE",
          "color": "#FFFFFF",
          "border_radius": "4px"
        },
        "secondary": {
          "background_color": "#FFFFFF",
          "color": "#6200EE",
          "border": "1px solid #6200EE"
        }
      },
      "input_styles": {
        "default": {
          "background_color": "#FFFFFF",
          "border": "1px solid #CED4DA",
          "border_radius": "4px"
        },
        "focus": {
          "border": "2px solid #6200EE"
        },
        "error": {
          "border": "2px solid #F44336"
        }
      },
      "card_styles": {
        "background_color": "#FFFFFF",
        "box_shadow": "0 2px 4px rgba(0,0,0,0.1)",
        "border_radius": "4px",
        "padding": "20px"
      },
      "form_styles": {
        "label": {
          "font_size": "16px",
          "color": "#757575"
        },
        "input": {
          "margin_top": "8px"
        },
        "error_message": {
          "color": "#F44336",
          "font_size": "14px"
        }
      },
      "navigation_styles": {
        "background_color": "#6200EE",
        "color": "#FFFFFF",
        "hover_effect": {
          "background_color": "#3700B3"
        }
      }
    },
    "animations": {
      "transitions": {
        "button": "background-color 0.3s ease",
        "input_focus": "border-color 0.3s ease"
      },
      "hover_effects": {
        "button": {
          "background_color": "#3700B3"
        }
      },
      "loading_states": {
        "spinner_color": "#6200EE"
      },
      "page_transitions": "fade-in 0.5s ease-in-out"
    },
    "responsive_design": {
      "breakpoints": {
        "small": "600px",
        "medium": "960px",
        "large": "1280px"
      },
      "mobile_first_approach": true,
      "grid_system": "8 columns on small, 12 columns on medium and above",
      "component_adaptations": {
        "button": {
          "small": {
            "padding": "12px 24px"
          },
          "medium": {
            "padding": "16px 32px"
          }
        }
      }
    }
  }
}
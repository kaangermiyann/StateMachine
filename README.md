# StateMachine

This is the way to get the asked attribute with all values.. Then you can get asked value of asked attribute
!!
### response = next((attr for attr in context['attributes'] if attr['attribute']['attributeCode'] == 'TermType'),None)
### response['values'][0]['value'] is the example

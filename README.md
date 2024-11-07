@{if(empty(outputs('Get_ID_of_Capability')?['body/_ge_capabilityowner_value']), '', concat('/systemusers(', outputs('Get_ID_of_Capability')?['body/_ge_capabilityowner_value'], ')'))}
